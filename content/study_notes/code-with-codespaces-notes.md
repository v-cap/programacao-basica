# [GitHub Skills](https://skills.github.com/)[^1]

Aprender como usar o GitHub com cursos interativos projetados para iniciantes e profissionais experientes.

## Criando códigos com o GitHub _Codespaces_

O GitHub _codespaces_ é um ambiente de desenvolvimento hospedado na nuvem.

Para iniciar, é possível criar um _codespace_ a partir de um modelo, ou a partir de qualquer ramo (_branch_) ou _commit_ num repositório.

### Passo 1: 
 - Criar o primeiro _codespace_ e enviar (_push_) código.
 - É possível customizar o _codespaces_ enviando (_commit_) arquivos de configuração para o repositório (_configuration-as-code_)
   - Isso cria uma configuração repetível para _codespaces_ para todos os usuários do projeto.
   - Cada _codespace_ criado é hospedado no GitHub, num conteiner Docker que é executado numa máquina virtual.
   - É possível escolher o tipo de máquina que se deseja utilizar dependendo dos recursos de que se necessita.
 - Pode-se:
   - Criar um _codespace_ a partir de um repositório.
   - Enviar (_push_) código do _codespace_ para o repositório.
   - Utilizar o VSCode para desenvolver código.
   - Personalizar o _codespace_ com imagens customizadas.
   - Gerenciar o _codespace_.
 - Para inicar um _codespace_ no ramo principal do repositório:
   - Na página inicial do repositório, clicar no botão verde `<> Code`.
   - Depois, clicar na aba codespace, e no botão `Criar codespace em main`.

### Passo 2: Adicionar uma imagem customizada ao _codespace_:
 - É possível configurar um _container_ de desenvolvimento para um repositório de modo que qualquer _codespace_ criado para o referido repositório gerará um ambiente de desenvolvimento sob medida e completo com todas as ferramentas e ambientes de execução (_runtimes_) necessários para se trabalhar num projeto específico.
 - _Conteineres_ de desenvolvimentop, ou _dev containers_, são _containers_ Docker especificamente configurados para prover um ambiente de desenvolvimento completo
  - Quando trabalhando em um _codespace_, estamos utilizando um _dev container_ instalado e configurado numa máquina virtual.
 - Um arquivo _dev container_ é um arquivo JSON que permite que sejam customizadas a imagem padrão que executa o _codespace_ e as configurações do VSCode. Permite ainda que se execute código customizado, se realize encaminhamento de portas (_forward ports_), e muito mais.
 - Para adicionar um arquivo `devcontainer.json` e uma imagem customizada a um repositório, siga as orientações apresentadas no __passo 2__ do curso [_Code with Codespaces_](https://github.com/skills/code-with-codespaces).
 - Uma lista de imagens disponíveis pode ser encontrada no repositório [devcontainers](https://github.com/devcontainers).
 - Mais informações sobre _dev containers_ podem ser encontradas em [_Introduction to dev containers_](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration/introduction-to-dev-containers).
   

<!-- 
> [!NOTE]
>  - `.md` é uma extensão que cria um arquivo [_Markdown_](https://www.markdownguide.org/). [Sobre _Markdown_](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
>  - [Curso comunicando-se com _Markdown_](https://github.com/skills/communicate-using-markdown). 
 - Nos _commits_ é possível inserir uma mensagem curta que descreve quais alterações foram realizadas. Essa mensagem ajuda outras pessoas a saber o que foi incluído no _commit_.

### Passo 3: Abra uma solicitação _pull_ (_pull request_) 
 - A colaboração acontece numa solicitação _pull_. Ela exibe as alterações no seu ramo para as outras pessoas e lhes permite aceitar, rejeitar, ou sugerir mudanças adicionais ao ramo.
 - A solicitação _pull_ mantem as mudanças realizadas num ramo e propõe aplicá-las ao ramo _main_. [Sobre solicitações pull](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).
 - Atividade: Crie uma solicitação pull.
  - Para criar uma requisição _pull_ automaticamente, clicar em `Compare and pull request`.
  - Para configurar uma requisição _pull_ manualmente:
    - Clicar na aba _pull requests_.
    - Clicar em _New pull request_.
    - Assegurar que o ramo _main_ está selecionado na _droplist_ base.
    - Na _droplist_ compare selecionar `my-first-branch`.
    - Clicar criar requisição _pull_.
    - Insira um título para a requisição _pull_.

### Passo 4: Mescle (_merge_) sua solicitação _pull_
 - Um _merge_ adiciona as mudanças da sua solicitação _pull_ e de um ramo secundário ao seu ramo _main_. [Sobre merges](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request).
 - Atividade: mescle a solicitação pull.

### Finalizado!
>[!IMPORTANT]
> Recursos para aprender mais e se desenvolver!!
>  - Para estudantes: [Student Developer Pack](https://education.github.com/pack).
>  - Cursos do [GitHub Skills](https://github.com/skills).
>  - [Documentos para iniciar no GitHub](https://docs.github.com/en/get-started).
>  - Onde encontrar projetos para contribuir: [GitHub Explore](https://github.com/explore).
>  - [Página de status do GitHub](https://www.githubstatus.com/). -->

[^1]: Os conteúdos dessa nota de estudos foram traduzidos do curso [_Code with Codespaces_](https://github.com/skills/code-with-codespaces), disponível no portal [GitHub Skills](https://skills.github.com/).
