# Aula 1

### Introdução ao Desenvolvimento Web

#### Arquitetura de um Site

A arquitetura de um site é como um site é organizado estruturalmente, entre páginas, menus, categorias e fluxos. Dessa forma, contruindo-se uma interface que favorece o usuário. Para isso, é importante definir alguns termos, dos quais são fundamentais para arquitetar um site, sendo eles:

- **Escopo**: Projetação e definção do que o projeto vai ter ou não. Exemplos: objetivo, funcionalidades, público alvo e restrições que delimitam o que pode ser feito.

- **Prototipação**: Simulação do site e suas funcionalidades antes do desenvolvimento técnico. Servindo para testar ideias, validar layouts e estabelecer um bom fluxo. 

- **UX (User Experience)**: Estabelececimento de um conjunto de elementos e estratégias para aprimorar a experiência do usuário. Bucando uma navegação intuitiva, eficiente e agradável.

#### Versionamento e Deploy

- **Versionamento**: Registros das alterações feitas ao longo do tempo no projeto, chamado também de "controle de versões". Se faz muito importante para permitir um trabalho em equipe mais eficiente através do uso de branches (ramificações). Também, permite o acesso a versões específicas, servindo até mesmo como um "backup", dando espaço para testes que não comprometam o projeto como um todo. A ferramenta mais utilizada para isso é o Git, o qual faz o gerenciamento para o upload do projeto em plataformas como o GitHub, GitLav e BitBucket.

- **Deploy**: Processo de implantação da aplicação em um ambiente acessível aos usuários finais. Os deploys podem ser feitos de forma manual ou automatizados. Quando feito de forma automatizada, a publicação da aplicação é feita juntamente ao "push" do projeto à ramificação principal (main). Ferramentas de automação como CI (Continuous Integration) e CD (Continuous Delivery) garantem que haja uma verificação de erros, validação da build a atualização automática do projeto. Ferramentas comuns utlizadas para deploy são: GitHub Actions, GitLab CI, Jenkins e Docker.

- **Monitoramento**: Após o deploy há a necessidade de monitoramento de parâmetros como performance, bugs, consumo de hardware, logs e tempo de resposta. Para isso exitem ferramentas como Datadog e New Relic.

- **Boas Práticas**:
    - Separar ambientes
    - Nunca testar direto em produção.
    - Nunca fazer deploy direto na main sem revisão
    - Usar Pull Requests
    - Automatizar testes
    - Monitorar após deploy
    - Ter plano de rollback

#### Introdução ao JavaScript

JavaScript é uma linguagem de programação interpretada, criada para tornar páginas web dinâmicas e interativas. Está presente em praticamente toda aplicação moderna atual, devido seu alto poder de manipulação de interface, comunicação com os servidores e APIs.

- **Vanilla JS**: É o JavaScript puro, sem dependencias externas.

##### Frameworks

Framework é uma estrutura pronta de desenvolvimento, a qual provê organização, padronização de código, ferramentas integradas, boas práticas e bibliotecas embutidas.

- **Frameworks Front-End**: Responsáveis pelo setor que é executado no navegador do usuário. Exemplos: React, Vue.js e Angular.

- **Frameworks Back-End**: Responsáveis pelo setor que é executado no servidor. Exemplos: Express.js e NestJS.

    - Website Builders: São ferramentas que permitem criar sites sem a necessidade de codificação manual. Facilitam o desenvovimento, mas limitam a flexibilidade.

#### Servidores e Hospedagem / CMS

- **Servidor**: É um computador (físico ou virtual) que, armazena arquivos do site, processa requisições e responde usuários via internet.
    - **Servidor Web**: Responsável por entregar arquivos. Exemplo: Apache HTTP Server.
    - **Servidor de Aplicação**: Processa lógica (Node, PHP, Python etc.). Exemplo: Node.js.
    - **Servidor de Banco de Dados**: Armazena dados estruturados. Exemplo: MySQL.

- **Hospedagem**: É o serviço que disponibiliza servidores para seu site ficar online.
    - **Cloud Hosting**: Infraestrutura escalável sob demanda. Exemplos: Amazon Web Services, Google Cloud e Microsoft Azure.

- **CMS**: É um sistema que permite criar e gerenciar conteúdo sem precisar programar. Fornece: painel administrativo, editor de páginas, sistema de usuários, plugins e temas. O mais utilizado no mundo é o WordPress.

#### Bancos de dados NoSQL

Bancos de dados NoSQL são não-relacionais, ou seja, não seguem o modelo de tabelas fixas e não dependem exclusivamente do SQL. Dessa forma, permitem interações dinâmicas e armazenamento de uma variedade de dados. Além disso, apresenta escalabilidade horizontal, fazendo com que os dados possam ser distribuídos em múltiplos servidores.