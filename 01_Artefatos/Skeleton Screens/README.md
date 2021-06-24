![Logo da Nasajon](../../logoNasajon.png "Logo da Nasajon")
# Processos e Documentos de Arquitetura
Documentação de auxílio ao desenvolvimento de software da Nasajon Sistemas.

---

## Skeleton screens <!--- Inserir título da especificação do componente a ser documentado -->

<!--- Descrever de forma resumida o que é esse componente e quando haver limitações informar. Além de inserir uma imagem dele em seu uso mais recorrente. -->
De acordo com os padrões de design advindos do site [Nielsen Norman Group (NN/g)](https://www.nngroup.com/articles/animation-purpose-ux/ "site Nielsen Norman Group") pertecente ao Jakob Nielsen e Don Norman, o coneito de "*Skeleton screens*" é:
> (a placeholder UI that looks like a wireframe of the loading page, with no content) that is animated by a light glare moving across it.
Que conforme a tradução do Google se refere a uma:
> “tela de esqueleto” (uma interface de usuário de espaço reservado que se parece com um wireframe da página de carregamento, sem conteúdo) que é animada por um clarão de luz se movendo através dela.

<details style="margin-bottom:20px;">
<style>.markdown-body>*:first-child {
    margin-top: 0 !important;
    display: none;
}</style>
  <!--- Inserir imagem do componente a ser documentado -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar a imagem do componente">
    <i class="fas fa-image" style="color: #2879d0;margin-right:10px;"></i> Imagem do componente</summary>
  <div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <p>Esse é o formato do componente Skeleton Screen sem o conteúdo estar dinâmico utilizando alguns elementos com fundo claro.</p>
    <p>Caso não visualize a imagem abaixo acessar por aqui a <a href="https://drive.google.com/file/d/1VLaB-qYHY5c-0MSsRu4n8cNDS0ltuBva/view?usp=sharing" target="_blank">imagem do Skeleton</a>.</p>
    <img src="exibindo Skeleton SEM conteudo dinamico.png" width="100%" height="auto" alt="Formato do componente Skeleton Screen utilizando tabela com fundo claro" />
    <hr>
    <p>Veja como o skeleton pode se apresentar de acordo com os dados a serem carregados. As linhas demarcadas representam a área em que o carregamento vai substituir o skeleton.</p>
    <p>Caso não visualize a imagem abaixo acessar por aqui a <a href="https://drive.google.com/file/d/1XcDhA1ZCuqurkx2g-uLXWC_OaxImPt-n/view?usp=sharing" target="_blank">visualização do skeleton com os dados</a>.</p>
    <img src="exibindo Skeleton COM conteudo dinamico.png" width="100%" height="auto" alt="Visualização do skeleton com os dados" />
    <hr>
    <p>Veja agora o zoom do skeleton com os dados a serem carregados.</p>
    <p>Caso não visualize a imagem abaixo acessar por aqui a <a href="https://drive.google.com/file/d/1cSg0T0JlpAKOXqajSX_Nc9gc4l9EsxDo/view?usp=sharing" target="_blank">visualização do zoom do skeleton com os dados</a>.</p>
    <img src="exibindo ZOOM Skeleton COM conteudo dinamico.png" width="100%" height="auto" alt="Visualização do zoom do skeleton com os dados" />
  </div>
</details>

<details style="margin-bottom:20px;">
  <!--- Descrever as formas em que esse componente deve ser usado. Além de ser interessante para cada formato ter sua imagem referente a cada uma dessas formas. -->
  <summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar as situações de uso do componente">
    <i class="fas fa-check" style="color: #2879d0;margin-right:10px;"></i> Situações de uso</summary>
  <div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <p>Continuando com a referência do site <a href="https://www.nngroup.com/articles/animation-purpose-ux/" target="_blank">Nielsen Norman Group (NN/g)</a> seu uso se dá:.</p>
    <blockquote>
      In addition to showing a transition between modes or views of data, animations are also helpful for communicating state changes that are not triggered by users’ actions. For example, loading indicators show that the system is not yet ready to accept input.
    </blockquote>
    <p>Ou seja, a tradução do Google se refere que:</p>
    <blockquote>
      Além de mostrar uma transição entre modos ou visualizações de dados, as animações também são úteis para comunicar mudanças de estado que não são acionadas pelas ações dos usuários. Por exemplo, os indicadores de carregamento mostram que o sistema ainda não está pronto para aceitar entradas.
    </blockquote>
    <hr>
    <p><b>Situação de uso 1</b></p>
    <!--- Seria a forma normal e mais recorrente de uso. -->
    <p>Aplicados em telas que têm uma demora no carregamento dos dados.</p>
  </div>
</details>

<details style="margin-bottom:20px;">
  <!--- Nessa parte entram as especificações de estilização do componente e fazer com que essas sejam detalhadas com os nomes das propriedades utilizadas no CSS. Prever seu comportamento quando redimensionar a tela do navegador sinalizando sua respectiva resolução. E em todos os casos é interessante colocar suas respectivas imagens, exceto da dimensão a não ser que essa possa ter casos específicos que requer mais atenção. -->
  <summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar a anatomia do componente">
    <i class="fas fa-draw-polygon" style="color: #2879d0;margin-right:10px;"></i> Anatomia do componente</summary>
  <div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <p><b>Dimensão</b></p>
    <!--- Vai detalhar o tamanho do componente que está sendo especificado. -->
    <p>Vai depender do dado final a ser carregado, possuindo a seguir algumas alturas pré-definidas.</p>
    <p><u>Largura</u></p>
    <!--- width: Detalhar; -->
    <p>Será aplicado o bom senso para manter a harmonia do Skeleton, projetando o comprimento em que o dado a ser carregado irá ser exibido.</p>
    <p><u>Altura</u></p>
    <!--- height: Detalhar; -->
    <p>Para cada altura mencionada a seguir foi adotado de acordo com o espeçamento entre linhas aos dados a serem exibidos, pois mesmo que possuem uma fonte com altura semelhante o que irá determinar a altura da forma do Skeleton será o espaço entre cada linha de texto.</p>
    <p>Onde o protótipo será representado apenas a ideia, pois na aplicação possa ser que as alturas aplicadas tenham que ser ajustadas para representar a transição mais próxima para quando as formas do Skeleton se transformarem nos dados a serem carregados.</p>
    <p>Para altura em que o espaçamento entre linhas é grande, com fonte de uns 15px ou mais (quando a fonte for um tamanho muito grande é provável que a altura da forma do Skeleton seja maior do que 18px).</p>
    <ul>
      <li>height: 18px;</li>
    </ul>
    <p>Para altura em que o espaçamento entre linhas é mediano, geralmente será para a altura de um badge de uns 17px.</p>
    <ul>
      <li>height: 15px;</li>
    </ul>
    <p>Para altura em que o espaçamento entre linhas é pequeno, com fonte de uns 16px.</p>
    <ul>
      <li>height: 10px;</li>
    </ul>
    <p>Para altura em que o espaçamento entre linhas é bem pequeno, com fonte de uns 13px.</p>
    <ul>
      <li>height: 9px;</li>
    </ul>
    <p><u>Arredondamento</u></p>
    <!--- Informar as áreas em que o componente possui o arredondamento, isso caso de fato possua, se não possui esse recurso retirar ele e editar a numeração dos itens da anatomia. Esse arrendamento comumente é aplicado nos cantos utilizando no CSS a propriedade border-radius. -->
    <p>Utilizados dois tipos:</p>
    <ol style="margin: -20px 0 20px 30px;">
      <li>Para altura das formas a partir de 15px, utilizando <b>border-radius: 4px;</b></li>
      <li>Para altura das formas a partir de 14px, utilizando <b>border-radius: 2px;</b></li>
    </ol>
    <p><u>Espaçamento</u></p>
    <!--- Informar as áreas em que o componente possui espaços. Esse espaçamento comumente é utilizado no CSS pelas propriedades padding e margin. -->
    <p>Vai variar para poder aplicar harmonização do Skeleton que mais se assemelha aos dados que serão carregados. Nas imagens a seguir visualizadas nos links abaixo o contorno azul é o skeleton.</p>
    <p>Utilizados dois tipos:</p>
    <ol style="margin: -20px 0 20px 30px;">
      <li><b>Espaçamento interno</b> - não se aplica.</li><!--- padding: Detalhar; -->
      <li><b>Espaçamento externo</b> - vai depender de como os dados finais são projetados na tela. A regra é manter um espaço entre eles de forma homogênea mantendo um padrão de espaçamento com as formas geométricas para a tela.</li><!--- margin: Detalhar; -->
    </ol>
  </div>
</details>

<details style="margin-bottom:20px;">
  <!--- Informar a estilização de todo o conteúdo textual que o componente poderá possuir, para os que não se aplicar apagar o item e renumerar ou então até criar outros seguindo a numeração. Caso tenha textos específicos que não podem ser facilmente localizados pelos itens descritos aqui neste item, use o recurso de inserir a imagem com os textos e sinalizar informando a aplicação dos estilos. -->
  <summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar as tipografia do componente">
    <i class="fas fa-font" style="color: #2879d0;margin-right:10px;"></i> Tipografia</summary>
  <div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <p>A tipografia utilizada é a que o sistema já possui por padrão e o Skeleton usará apenas formas geométricas para aplicar o carregamento do conteúdo.</p>
  </div>
</details>

<details style="margin-bottom:20px;">
  <!--- Detalhar como o componente irá se comportar. -->
  <summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar os comportamentos do componente">
    <i class="fas fa-retweet" style="color: #2879d0;margin-right:10px;"></i> Comportamento</summary>
  <div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <p>A animação do Skeleton terá os seguintes efeitos:</p>
    <p><u>Na transição INICIAL</u></p>
    <ul style="margin-top: -15px;">
      <li>Delay = 1ms</li>
      <li>Navigate to = transição FINAL</li>
      <li>Animate = Smart animate</li>
      <li>Curve = Ease In And Out</li>
      <li>Duration = 1000ms</li>
    </ul>
    <p><u>Na transição FINAL</u></p>
    <ul style="margin-top: -15px;">
      <li>Delay = 9ms</li>
      <li>Navigate to = transição INICIAL</li>
      <li>Animate = Dissolve</li>
      <li>Curve = Linear</li>
      <li>Duration = 1000ms</li>
    </ul>
    <p><u>Na transição do CONTEÚDO carregado</u></p>
    <ul style="margin-top: -15px;">
      <li>Animate = Dissolve</li>
      <li>Curve = Ease Out</li>
      <li>Duration = 800ms</li>
    </ul>
  </div>
</details>

<details style="margin-bottom:20px;">
  <!--- Inserir os protótipos do componente a ser documentado -->
  <summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar os cenários do componente">
    <i class="fab fa-figma" style="color: #2879d0;margin-right:10px;"></i> Cenário</summary>
  <div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <p><a href="https://www.figma.com/proto/UCIWxoWAioHrFnG4vMYl0o/04-Templates?page-id=101%3A64&node-id=112%3A350&viewport=-307%2C647%2C0.1657804399728775&scaling=min-zoom" target="_blank">Protótipo navegável no Figma com o Skeleton Sreens no fundo claro</a>.</p>
    <hr>
    <p><a href="https://www.figma.com/proto/UCIWxoWAioHrFnG4vMYl0o/04-Templates?page-id=112%3A591&node-id=112%3A604&viewport=617%2C497%2C1.1153100728988647&scaling=min-zoom" target="_blank">Protótipo navegável no Figma com o Skeleton Sreens no fundo escuro</a>.</p>
  </div>
</details>

<details style="margin-bottom:20px;">
  <!--- Detalhar as referências de grandes empresas (Google, Amazon, Microsoft, etc) que usam o recurso do componente que está sendo especificado. -->
  <summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar os benchmarks do componente">
    <i class="fas fa-building" style="color: #2879d0;margin-right:10px;"></i> Benchmark</summary>
  <div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <p>Empresas como Facebook, Linkedin, Google, Youtube, banco Itaú, Nubank entre outras utilizam esse recurso digital para proporcionar uma boa UX. Vide alguns dos exemplos citados aqui no link: <a href="https://brasil.uxdesign.cc/como-as-skeletons-screens-podem-ajudar-a-aprimoram-experi%C3%AAncia-de-uso-do-seu-produto-987c736651ca" target="_blank">Sobre skeleton screens e Benchmark - site</a>.</p>
    <p>A seguir algumas referências de mercado no uso do skeleton screen.</p>
    <hr>
    <p><u>Google Drive</u></p>
    <!--- Detalhar o comportamento de como essa empresa que está sendo listada como referência usa esse componente. -->
    <p>Inicialmente aparece o lado esquerdo parcialmente populado e do meio com o load circular tradicional, em seguida cards deslizam da direita para a esquerda contendo ao mesmo tempo o surgimento do meio para baixo de outras informações. Nos cards o skeleton tem um efeito sutil e seu conteúdo vai preenchendo da esquerda para a direita. Esse conteúdo apresentado se encontra na opção de Prioriedade do Google Drive, nos demais locais ele exibe outras animações.</p>
    <p>Caso não visualize o gif animado abaixo, acessar por aqui o <a href="https://drive.google.com/file/d/1pIbYfNSc8BhwbsnHkDB5BOXJ9wCU28PM/view?usp=sharing" target="_blank">efeito de Skeleton screens no Google Drive</a>.</p>
    <img src="Referencia-1_GoogleDrive.gif" width="100%" height="auto" alt="Visualizar efeito de Skeleton screens no Google Drive" />
    <hr>
    <p><u>Youtube</u></p>
    <!--- Detalhar o comportamento de como essa empresa que está sendo listada como referência usa esse componente. -->
    <p>Inicialmente aparece as cores de fundo do lado esquerdo e do direito contendo o skeleton sem efeito aplicado neles, tudo estático. Depois todos os skeletons do lado direito somem e vai surgindo aos poucos, aparecendo de forma parcial nos itens que o texto já carregou e as imagens vem a seguir aparecendo de cima para baixo, podendo ser perceptível ou não dependendo da demora do conteúdo ir preenchendo o skeleton e por último o lado esquerdo vem preenchendo com o texto vindo de cima para baixo com um leve efeito no fundo.</p>
    <p>Caso não visualize o gif animado abaixo, acessar por aqui o <a href="https://drive.google.com/file/d/1AxUyVHLGv3TSizmP-5CQiqEH_R9IYuzI/view?usp=sharing" target="_blank">efeito de Skeleton screens no Youtube</a>.</p>
    <img src="Referencia-2_Youtube.gif" width="100%" height="auto" alt="Visualizar efeito de Skeleton screens no Youtube" />
  </div>
</details>

<details style="margin-bottom:20px;">
  <!--- Inserir todas as referências utilizadas para especificar esse componente -->
  <summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar as referências do componente">
    <i class="fas fa-book" style="color: #2879d0;margin-right:10px;"></i> Referências</summary>
  <div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <p><a href="https://www.figma.com/community/file/834358460009249905" target="_blank">Skeleton loader - Figma</a></p>
    <p><a href="https://www.figma.com/community/file/968801107739343872" target="_blank">Skeleton components - Figma</a></p>
    <p><a href="https://codepen.io/vinayakkulkarni/pen/XZwaBp" target="_blank">Skeleton screens - HTML/CSS</a></p>
    <p><a href="https://brasil.uxdesign.cc/como-as-skeletons-screens-podem-ajudar-a-aprimoram-experi%C3%AAncia-de-uso-do-seu-produto-987c736651ca" target="_blank">Sobre Benchmark - site</a></p>
    <p><a href="https://www.nngroup.com/articles/animation-purpose-ux/" target="_blank">Sobre Skeleton screens - site</a></p>
  </div>
</details>
