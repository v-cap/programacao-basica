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

### Passo 3: Customizando o _codespace_:
 - É possível customizar o codespace adicionando extensões e recursos do VSCode, configurando os requisitos do sistema hospedeiro, etc.
 - Isso é feito através do arquivo 'devconteiner.json'.

### Passo 4: Personalizar o _codespace_:
 - Ao se utilizar um ambiente de desenvolvimento é importante que se customize configurações e ferramentas para suas preferências e fluxos de trabalho (_workflows_).
 - O GitHub _codespaces_ oferece duas formas principais de se personalizar o codespace:
  - _Settings sync_ com o VSCode
  - _dotfiles_
 - _Dotfiles_ são arquivos e pastas num sistema Unix iniciando com ".", que controlam a configuração de aplicações e _shells_ do sistema. É possível armazenar e gerenciar os _dotfiles_ num repositório GitHub.
 - Habilitar um _dotfile_ para o _codespace_
 - Adicionar um _dotfile_ ao repositório e executá-lo no _codespace_.

### Finalizado!
>[!IMPORTANT]
> Recursos para aprender mais e se desenvolver!!
>  - [Desenvolvendo num _codespace_](https://docs.github.com/en/codespaces/developing-in-codespaces/developing-in-a-codespace) - Aprenda como apagar um codespace, abrir um codespace existente, conectar a uma rede privada, encaminhar portas, e mais.
>  - [Configure seu repositório](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/introduction-to-dev-containers) - Aprenda como configurar especificações mínimas de máquina para um _codespace_, adicionar _badges_, configurar um repositório _template_, e mais.
>  - [Personalize o GitHub _codespaces_](https://docs.github.com/en/codespaces/customizing-your-codespace/personalizing-github-codespaces-for-your-account) - Aprenda como configurar sincronização para seu _codespace_, acrescentar _dotfiles_, configurar região padrão, configurar editor padrão, e mais.
>  - [Faça um _prebuild_ do seu _codespace_](https://docs.github.com/en/codespaces/prebuilding-your-codespaces/about-github-codespaces-prebuilds).
>  - [Gerencie seu _codespace_](https://docs.github.com/en/codespaces/managing-codespaces-for-your-organization/enabling-github-codespaces-for-your-organization).

[^1]: Os conteúdos dessa nota de estudos foram traduzidos do curso [_Code with Codespaces_](https://github.com/skills/code-with-codespaces), disponível no portal [GitHub Skills](https://skills.github.com/).
