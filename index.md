(site do Arquitetura na versão de teste) o oficial é esse [Processos e Documentos de Arquitetura](https://nasajon.github.io/Arquitetura/)

# Home

* Backend
    * [Arquitetura de APIs](Backend/arquitetura-de-APIs/README.md)
    * [Cursos Recomendados](Backend/cursos.md)
* Frontend
    * [Documentação Nasajon UI](http://ui.nasajon.com.br.s3-website-us-west-2.amazonaws.com/)
    * [Cursos Recomendados](Frontend/cursos.md)
    
* DevOps
    * Processos
        * 1 Sincronização
            * 1.1 [Instalação](DevOps/sincronizacao/instalacao-de-sincronizacao.md)
            * 1.2 [Movimentação de base](DevOps/sincronizacao/movimentacao-de-base.md)
            * 1.3 [Informação inconsistente](DevOps/sincronizacao/informacao-inconsistente.md)
            * 1.4 [Serviço parado](DevOps/sincronizacao/servico-parado.md)
            * 1.5 [Roteamento](DevOps/sincronizacao/roteamento.md)
            * 1.6 [Encaminhamento de pacote](DevOps/sincronizacao/encaminhamento-de-pacote.md)
        * 2 Gestão de incidêntes
            * 2.1 [Monitoramento](DevOps/gestao_incidente/monitoramento.md)
            * 2.2 Infraestrutura
              * 2.2.1 Alto consumo de CPU
              * 2.2.2 Lentidão das aplicações web
              * 2.2.3 Aplicação web indisponível
            * 2.3 Banco de dados
                * 2.3.1 [Alto consumo de CPU](DevOps/gestao_incidente/bd/consumo-de-cpu.md)
                * 2.3.2 [Serviço de Importação de Dados](DevOps/servico_importacao_dados/importacao_de_dados.md)
            * 2.4 Criação de RCA
                * 2.4.1 Análise e criação do documento
        * 3 Ciclo de vida de desenvolvimento dos sistemas
            * [3.1 Projeto pipeline CI/CD](DevOps/CVDS/projeto_pipeline.md)
            * [3.2 Processo de desenvolvimento](DevOps/CVDS/processo_desenvolvimento.md)
            * [3.3 Processo de atualização](DevOps/CVDS/processo_atualizacao.md)
    * Cookbooks
        * Ansible
            * [Criação de aplicação kubernetes para role k8s_app](DevOps/Cookbooks/ansible/k8s_app_template.md)
        * AWX (Ansible Tower)
            * [Deploy dos sistemas web](DevOps/Cookbooks/awx/deploys_sistemas_web.md)
            * [Criação de usuário ses](DevOps/Cookbooks/awx/criacao_usuario_ses.md)
            * [Configuração de servidor windows](DevOps/Cookbooks/awx/configuracao_servidor_windows.md)
            * [Atualização de Clientes Nuvem](DevOps/Cookbooks/awx/atualizacao_clientes_nuvem_awx.md)
            * [Manutenção de base de dados de Clientes Nuvem](DevOps/Cookbooks/awx/manutencao_clientes_nuvem_awx.md)        
* Cookbooks
    * [Como enviar emails nos sistemas](Cookbooks/como-enviar-email.md)
    * [Como criar documentos em PDF nos sistemas](Cookbooks/como-criar-documentos-pdf.md)
    * [Como criar permissões para o sistema](Cookbooks/como-criar-permissoes.md)
    * [Como Criar XML (ou JSON) a partir da entidade](Cookbooks/como-criar-xml-apartir-da-entidade.md)
    * [Como configurar o Xdebug no Vscode](Cookbooks/como-configurar-xdebug-no-vscode.md)
    * [Como cachear uma resposta de um método](Cookbooks/como-cachear-resposta.md)
    * [Como adicionar tabelas para a sincronia.](Cookbooks/como-adicionar-tabelas-para-sincronia.md)
    * [Como criar configuraçes em Web Configurações.](Cookbooks/como-criar-configuracoes.md)
    * [Como aplicar layout de impressao](Cookbooks/como-aplicar-layout-de-impressao.md)
    * [Como enviar notificações nos sistemas Web e Mobile](Cookbooks/notificações/como-utilizar-envio-notificacoes.md)
    * [Como adicionar o health-check-bundle a uma aplicação](Cookbooks/como-adicionar-o-health-check-bundle-a-uma-aplicacao.md)
    * [Configuração do ambiente de desenvolvimento](Cookbooks/como-configurar-ambiente-desenvolvimento)
* DesignOps

    **DesignOps** refere-se à orquestração e otimização de pessoas, processos e ofício, a fim de amplificar o valor e o impacto do design em escala. [[NN/g Nielsen Norman Group, 2019](https://www.nngroup.com/articles/design-operations-101/)]
    * [01 Áreas e suas competências](06_Areas/)
    * [02 Base de Conhecimento e Treinamentos](02_BaseConhecimento-Treinamentos/)
    * [03 Ferramentas e Recursos](03_Ferramentas-Recursos/)
    * [04 Processos](04_Processos/)
    * [05 Cerimônias](05_Cerimonias/)
    * [06 Artefatos](01_Artefatos/)

<details style="margin-bottom:20px;">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<summary style="
    background-color: #ddd;
    padding: 10px;
    font-weight: bold;
    border-radius: 4px 4px 0 0;
    cursor:pointer;"
    title="Clique aqui para visualizar como acessar um template personalizado">
    <i class="fas fa-file-video" style="color: #2879d0;margin-right:10px;"></i> Vídeo explicativo sobre a organização dos conteúdos da equipe DesignOps</summary>
<div style="
    border: 1px solid #ddd;
    border-radius: 0 0 4px 4px;
    padding: 15px;">
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
