# Bemobi Hire.me Implementation
Implementação do projeto Hire.me desenvolvida por Felipe Paixão Lohnefink

## Considerações Gerais

Apesar da minha experiência anterior com a tecnologia Ruby on Rails para desenvolvimento Web, devido a grande quantidade de tempo sem a utilizar, eu optei por desenvolver minha solução sobre a linguagem Java por ser a linguagem utilizada no dia-a-dia da empresa. Para isto, durante esta semana que tive para desenvolver, eu estudei extensivamente algumas tecnologias relacionadas e descartei também algumas que julguei que não pertenciam ao escopo do projeto.

Foram elas:

- Framework Spring para Dependency Injection
- Gerenciador de Dependências Maven
- JDBD neste novo contexto
- JPA e Hibernate neste novo contexto
- H2 in memory Database

Também revisei alguns conceitos como:

- RESTful Web Services over HTTP
- XML e JSON based APIs

Apesar de ter compreendido bem todos os conceitos e ter conseguido implementar pequenos sistemas no processo eu não consegui, no tempo restrito que me foi disponibilizado e em virtude também da época do ano já naturalmente mais conturbada, chegar a versão final do projeto como eu gostaria. Apesar disso, envio a vocês os 3 pequenos projetos para que sejam avaliados dentro de cada um de seus respectivos escopos. Explico brevemente cada um deles.

### Projeto 1 - BemobiXmlRESTfulWebService

Este primeiro projeto permite o gerenciamento de "links" (que é como eu chamo as urls armazenadas com seus respectivos alias) através de um cliente HTTP (como o CURL, por exemplo). Através do Browser é possível verificar todos os links cadastrados e entrar nos detalhes de cada um deles individualmente obtendo sempre a resposta do servidor no formato de XML.

### Projeto 2 - BemobiDatabaseInteraction

Neste segundo projeto é possível utilizar 3 tipos diferentes de interface com o banco de dados implementado:
- Primeiro a tecnologia JDBD através de seus DAOs e queries;
- Em segundo lugar utilizando a abordagem JPA através de seus repositórios e facilidades de comunicação com o banco;
- E por último a versão mais alto nível proporcionada pela abordagem Spring Data acrescentando mais uma camada de abstração ao processo;

### Projeto 3 - BemobiSpringMVC

Neste terceiro e último projeto foi implementado uma interface de login com validação de usuário e senha através de um formulário simples. O destaque aqui fica por conta da implemantação da solução MVC utilizando o Design Pattern chamado Front Controller.

## Considerações Finais

Como eu já mencionei, apenas me faltou o tempo para unir todos estes conceitos em um único projeto.

Agradeço muito a oportunidade dada a mim pela Bemobi e aguardo um feedback assim que possível.

Obrigado!
