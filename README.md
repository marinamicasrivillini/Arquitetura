![Logo da Nasajon](logoNasajon.png "Logo da Nasajon")
# Processos e Documentos de Arquitetura
Documentação de auxílio ao desenvolvimento de software da Nasajon Sistemas.

---

<details style="margin-bottom:20px;">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar conteúdos do Backend">
    Backend</summary>
<div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <ul>
    <li><a href="Backend/arquitetura-de-APIs/README.md" target="_blank">Arquitetura de APIs</a></li>
    <li><a href="Backend/cursos.md" target="_blank">Cursos Recomendados</a></li>
    </ul>
</div>
</details>

<details style="margin-bottom:20px;">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar conteúdos do Frontend">
    Frontend</summary>
<div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <ul>
    <li><a href="http://ui.nasajon.com.br.s3-website-us-west-2.amazonaws.com/" target="_blank">Documentação Nasajon UI</a></li>
    <li><a href="Frontend/cursos.md" target="_blank">Cursos Recomendados</a></li>
    </ul>
</div>
</details>

<details style="margin-bottom:20px;">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar conteúdos do DevOps">
    DevOps</summary>
<div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <h3>Processos</h3>
    <p>Sincronização</p>
    <ul>
        <li><a href="DevOps/sincronizacao/instalacao-de-sincronizacao.md" target="_blank">Instalação</a></li>
        <li><a href="DevOps/sincronizacao/movimentacao-de-base.md" target="_blank">Movimentação de base</a></li>
        <li><a href="DevOps/sincronizacao/informacao-inconsistente.md" target="_blank">Informação inconsistente</a></li>
        <li><a href="DevOps/sincronizacao/servico-parado.md" target="_blank">Serviço parado</a></li>
        <li><a href="DevOps/sincronizacao/roteamento.md" target="_blank">Roteamento</a></li>
        <li><a href="DevOps/sincronizacao/encaminhamento-de-pacote.md" target="_blank">Encaminhamento de pacote</a></li>
    </ul>
    <p>Gestão de incidêntes</p>
    <ul>
        <li><a href="DevOps/gestao_incidente/monitoramento.md" target="_blank">Monitoramento</a></li>
        <li>Infraestrutura
            <ul>
            <li>Alto consumo de CPU</li>
            <li>Lentidão das aplicações web</li>
            <li>Aplicação web indisponível</li>
            </ul>
        </li>
        <li>Banco de dados
            <ul>
            <li><a href="DevOps/gestao_incidente/bd/consumo-de-cpu.md" target="_blank">Alto consumo de CPU</a></li>
            <li><a href="DevOps/servico_importacao_dados/importacao_de_dados.md" target="_blank">Serviço de Importação de Dados</a></li>
            </ul>
        </li>
        <li>Criação de RCA
            <ul>
            <li>Análise e criação do documento</li>
            </ul>
        </li>
    </ul>
    <p>Ciclo de vida de desenvolvimento dos sistemas</p>
    <ul>
        <li><a href="DevOps/CVDS/projeto_pipeline.md" target="_blank">3.1 Projeto pipeline CI/CD</a></li>
        <li><a href="DevOps/CVDS/processo_desenvolvimento.md" target="_blank">Processo de desenvolvimento</a></li>
        <li><a href="DevOps/CVDS/processo_atualizacao.md" target="_blank">Processo de atualização</a></li>
    </ul>
    <h3>Cookbooks</h3>
    <p>Ansible</p>
    <ul>
        <li><a href="DevOps/Cookbooks/ansible/k8s_app_template.md" target="_blank">Criação de aplicação kubernetes para role k8s_app</a></li>
    </ul>
    <p>AWX (Ansible Tower)</p>
    <ul>
        <li><a href="DevOps/Cookbooks/awx/deploys_sistemas_web.md" target="_blank">Deploy dos sistemas web</a></li>
        <li><a href="DevOps/Cookbooks/awx/criacao_usuario_ses.md" target="_blank">Criação de usuário ses</a></li>
        <li><a href="DevOps/Cookbooks/awx/configuracao_servidor_windows.md" target="_blank">Configuração de servidor windows</a></li>
        <li><a href="DevOps/Cookbooks/awx/atualizacao_clientes_nuvem_awx.md" target="_blank">Atualização de Clientes Nuvem</a></li>
        <li><a href="DevOps/Cookbooks/awx/manutencao_clientes_nuvem_awx.md" target="_blank">Manutenção de base de dados de Clientes Nuvem</a></li>
    </ul>
    <p>Cookbooks</p>
    <ul>
        <li><a href="Cookbooks/como-enviar-email.md" target="_blank">Como enviar emails nos sistemas</a></li>
        <li><a href="Cookbooks/como-criar-documentos-pdf.md" target="_blank">Como criar documentos em PDF nos sistemas</a></li>
        <li><a href="Cookbooks/como-criar-permissoes.md" target="_blank">Como criar permissões para o sistema</a></li>
        <li><a href="Cookbooks/como-criar-xml-apartir-da-entidade.md" target="_blank">Como Criar XML (ou JSON) a partir da entidade</a></li>
        <li><a href="Cookbooks/como-configurar-xdebug-no-vscode.md" target="_blank">Como configurar o Xdebug no Vscode</a></li>
        <li><a href="Cookbooks/como-cachear-resposta.md" target="_blank">Como cachear uma resposta de um método</a></li>
        <li><a href="Cookbooks/como-adicionar-tabelas-para-sincronia.md" target="_blank">Como adicionar tabelas para a sincronia</a></li>
        <li><a href="Cookbooks/como-criar-configuracoes.md" target="_blank">Como criar configuraçes em Web Configurações</a></li>
        <li><a href="Cookbooks/como-aplicar-layout-de-impressao.md" target="_blank">Como aplicar layout de impressao</a></li>
        <li><a href="Cookbooks/notificações/como-utilizar-envio-notificacoes.md" target="_blank">Como enviar notificações nos sistemas Web e Mobile</a></li>
        <li><a href="Cookbooks/como-adicionar-o-health-check-bundle-a-uma-aplicacao.md" target="_blank">Como adicionar o health-check-bundle a uma aplicação</a></li>
        <li><a href="Cookbooks/como-configurar-ambiente-desenvolvimento" target="_blank">Configuração do ambiente de desenvolvimento</a></li>
    </ul>
</div>
</details>

<details style="margin-bottom:20px;">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar conteúdos do DesignOps">
    DesignOps</summary>
<div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
    <p>DesignOps refere-se à orquestração e otimização de pessoas, processos e ofício, a fim de amplificar o valor e o impacto do design em escala.<a href="https://www.nngroup.com/articles/design-operations-101/" target="_blank">[NN/g Nielsen Norman Group, 2019]</a></p>
    <ol>
    <li><a href="06_Areas/">Áreas e suas competências</a></li>
    <li><a href="02_BaseConhecimento-Treinamentos/" target="_blank">Base de Conhecimento e Treinamentos</a></li>
    <li><a href="03_Ferramentas-Recursos/">Ferramentas e Recursos</a></li>
    <li><a href="04_Processos/">Processos</a></li>
    <li><a href="05_Cerimonias/">Cerimônias</a></li>
    <li><a href="01_Artefatos/">Artefatos</a></li>
    </ol>
    <h3>Vídeo explicativo sobre a organização dos conteúdos da equipe DesignOps</h3>
    <p>Nesse vídeo é explicado como nosso conteúdo de design está organizado.</p>
    <p>Caso não visualize o vídeo abaixo, acessar por aqui o <a href="https://drive.google.com/file/d/1vM1Omg5BXmNAhgS5SRJqy9A5GbxUXlk6/view?usp=sharing" target="_blank">Vídeo explicativo</a>.</p>
    <video controls width="100%" height="400" controls>
        <source src="Design/designOps.mp4" type="video/mp4">
        <object>
            <embed src="Template para Documentação.mp4" type="application/x-shockwave-flash" 
            allowfullscreen="false" allowscriptaccess="always">  		
        </object>
        Formato não suportado  
    </video>
</div>
</details>

---

Obs: Caso encontre algum passo ou problema não coberto por essa documentação, favor atualizá-la para ajudar outros devs que podem passar pelo mesmo problema.