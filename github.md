### Introdução ao GitHub

GitHub é uma plataforma de hospedagem de código-fonte e desenvolvimento colaborativo que utiliza o sistema de controle de versão Git. Foi lançada em 2008 e rapidamente se tornou a plataforma dominante para o desenvolvimento de software colaborativo. GitHub oferece funcionalidades como repositórios de código, controle de versão, gerenciamento de projetos, rastreamento de problemas e revisão de código, além de ser uma rede social para desenvolvedores.

### História do GitHub

#### Origem e Fundadores
GitHub foi fundado por Tom Preston-Werner, Chris Wanstrath, PJ Hyett e Scott Chacon. A ideia surgiu como uma forma de tornar o Git mais acessível, principalmente para desenvolvedores que não tinham muita familiaridade com a linha de comando.

#### Lançamento e Crescimento Inicial
A plataforma foi lançada em abril de 2008. Desde o início, GitHub atraiu desenvolvedores graças à sua interface amigável e às funcionalidades que facilitavam a colaboração. Em 2010, GitHub alcançou um marco significativo com 1 milhão de repositórios hospedados.

#### Aquisição pela Microsoft
Em junho de 2018, a Microsoft anunciou a aquisição do GitHub por 7,5 bilhões de dólares. A aquisição causou controvérsia inicialmente, mas a Microsoft assegurou que o GitHub continuaria operando de forma independente. Desde então, a Microsoft tem integrado GitHub a várias de suas ferramentas de desenvolvimento, como o Visual Studio Code.

### Funcionamento do GitHub

#### Repositórios
Um repositório (ou "repo") no GitHub é um espaço onde os projetos são armazenados. Cada repositório pode conter arquivos de código-fonte, arquivos de documentação, recursos e outros dados necessários para o projeto. Repositórios podem ser públicos (visíveis a todos) ou privados (restritos a colaboradores específicos).

#### Controle de Versão com Git
GitHub utiliza o Git, um sistema de controle de versão distribuído criado por Linus Torvalds em 2005. Com o Git, cada desenvolvedor tem uma cópia completa do histórico do projeto em seu repositório local. Isso facilita a colaboração e permite trabalhar offline.

#### Branches e Merges
No GitHub, é comum usar branches (ramificações) para trabalhar em novas funcionalidades ou correções de bugs de forma isolada do branch principal (geralmente chamado de "main" ou "master"). Quando uma funcionalidade está pronta, um merge (fusão) é realizado para integrar as alterações ao branch principal.

#### Pull Requests
Os pull requests (PRs) são uma das funcionalidades mais poderosas do GitHub. Um PR permite que um desenvolvedor notifique os mantenedores de um projeto sobre alterações que foram feitas em um branch. Outros colaboradores podem revisar e discutir essas alterações antes de elas serem integradas ao branch principal.

#### Issues e Project Boards
GitHub oferece uma funcionalidade de issues (problemas) para rastrear bugs, novas funcionalidades e outras tarefas. Issues podem ser comentadas, etiquetadas e atribuídas a membros da equipe. Além disso, project boards (quadros de projetos) permitem organizar issues e pull requests em um formato Kanban, facilitando o gerenciamento do projeto.

#### Ações e Automação
GitHub Actions é uma plataforma de integração contínua e entrega contínua (CI/CD) que permite automatizar fluxos de trabalho. Desenvolvedores podem criar scripts que são executados em resposta a eventos como commits, pull requests e releases.




### NOMENCLATURAS DO GITHUB

No GitHub, existem várias nomenclaturas e termos específicos que são fundamentais para entender como a plataforma funciona. Aqui estão alguns dos termos mais comuns e suas definições:

### Repositórios e Conteúdo

1. **Repository (Repositório)**: Um local onde os projetos são armazenados. Cada repositório pode conter múltiplos arquivos e pastas, além de um histórico completo de todas as mudanças feitas no projeto.

2. **Commit**: Uma snapshot (instantâneo) do estado atual do repositório. Cada commit tem um identificador único (hash) e contém uma mensagem descritiva das mudanças feitas.

3. **Branch**: Uma ramificação do repositório onde o desenvolvimento pode ocorrer isoladamente do branch principal. Permite trabalhar em novas funcionalidades ou correções de bugs sem afetar o código estável.

4. **Merge**: O processo de integrar mudanças de um branch para outro. Normalmente usado para incorporar alterações feitas em branches de desenvolvimento ao branch principal.

5. **Pull Request (PR)**: Uma solicitação para integrar mudanças de um branch para outro. Permite a revisão e discussão das alterações antes de serem integradas ao branch principal.

6. **Fork**: Uma cópia de um repositório que permite ao usuário experimentar livremente sem afetar o repositório original. Forks são frequentemente usados para contribuir com projetos de código aberto.

7. **Clone**: Uma cópia local de um repositório remoto. Permite ao usuário trabalhar no projeto localmente e sincronizar as alterações com o repositório remoto.

### Gerenciamento de Projetos

8. **Issue**: Uma unidade de trabalho que pode representar um bug, uma nova funcionalidade, uma tarefa ou uma pergunta. Issues podem ser comentadas, etiquetadas e atribuídas a membros da equipe.

9. **Milestone**: Um agrupamento de issues e pull requests em uma meta ou etapa específica do projeto. Ajuda a organizar o progresso e planejar lançamentos.

10. **Label (Etiqueta)**: Uma tag aplicável a issues e pull requests para categorizá-los ou priorizá-los. Labels podem ser personalizadas para atender às necessidades do projeto.

11. **Project Board**: Um quadro de gerenciamento de projetos estilo Kanban que permite organizar issues e pull requests em colunas como "To Do", "In Progress" e "Done".

### Colaboração e Automação

12. **Collaborator (Colaborador)**: Um usuário que tem permissões específicas para contribuir diretamente com um repositório. Colaboradores podem ter diferentes níveis de acesso, desde leitura até administração completa.

13. **Actions**: Fluxos de trabalho automatizados que podem ser configurados para executar tarefas em resposta a eventos no repositório, como commits ou pull requests. Usado para integração contínua (CI) e entrega contínua (CD).

14. **Webhook**: Uma callback HTTP que é acionada por eventos específicos em um repositório. Webhooks são usados para integrar o GitHub com outros serviços.

15. **Gist**: Um serviço de compartilhamento de trechos de código e notas. Cada Gist é um repositório Git, permitindo versionamento e fork.

16. **Release**: Um ponto específico no histórico do projeto que é significativo para o desenvolvimento, como uma nova versão do software. Releases incluem o código-fonte, notas de lançamento e arquivos binários.

17. **Wiki**: Uma coleção de páginas interligadas usada para documentar o projeto. Cada repositório pode ter sua própria wiki.

### Segurança e Controle

18. **Branch Protection**: Regras aplicáveis a branches para controlar como as alterações são feitas. Podem incluir requisitos como aprovação de pull requests e execução bem-sucedida de testes.

19. **Code Owners**: Arquivo que designa responsáveis por partes específicas do código. Quando mudanças são propostas, os code owners são automaticamente solicitados para revisão.

20. **Dependabot**: Um bot que ajuda a manter dependências atualizadas e seguras. Dependabot pode criar pull requests automaticamente para atualizar dependências quando novas versões são lançadas.

### Interface e Uso

21. **Markdown**: Uma linguagem de marcação leve usada para formatar texto em GitHub, como em arquivos README, issues e pull requests.

22. **README**: Um arquivo de texto (geralmente em Markdown) que fornece uma visão geral e documentação básica do projeto. Normalmente, é o primeiro arquivo que os visitantes veem em um repositório.

23. **GitHub Pages**: Um serviço que permite hospedar sites estáticos diretamente de um repositório GitHub. Usado com frequência para documentações e blogs.

Compreender essas nomenclaturas é essencial para utilizar o GitHub de maneira eficiente e colaborar efetivamente em projetos de software.