# Entregas

Este documento tem como objetivo reunir todas as entregas da disciplina de Engenharia de Software (MAC0332-MAC5783) da Universidade de São Paulo, ministrada pelo Prof. Dr. Pedro Henrique Dias Valle.

O grupo listado abaixo será responsável pelo desenvolvimento e pela documentação deste projeto.

- [Caio Groff](https://github.com/caiogroff-droid)
- Ísis A. Logullo
- Rodrigo Lira
- [Yago H. Pereira](https://github.com/yagohp)

## Entrega 1: Definição do Problema, Escolha da API e Planejamento Inicial
- [Documento com a descrição do problema a ser abordado e justificativa para a escolha da API](./definicao-problema.md)
- [Identificação do público-alvo da solução](./definicao-problema.md#identificação-do-público-alvo-da-solução)
- [Mapa de empatia](./mapa-empatia.md)
- [Estrutura inicial de backlog de funcionalidades](./definicao-backlog.md)
- Apoio ferramental que será utilizado para a gestão do projeto (GitLab, Kanban, Trello, Taiga, entre outras)
    - **GitHub Project** [Questibular](https://github.com/orgs/USP-EngSoft-MAC0332-MAC5783/projects/2) organização e documentação do  processo (iterações, Kanban etc.)
    - **GitHub** para versionamento de código e documentação do projeto
        - Repositório da API `descontinuado`
        - [Repositório da UI](https://github.com/USP-EngSoft-MAC0332-MAC5783/questibular-js-ui)
- Avaliação de diagnóstico (entregue à parte)


## Entrega 2: Especificação de Requisitos e Prototipação

- [x] Backlog de funcionalidades completo no formato de user stories (link dos [issues](https://github.com/USP-EngSoft-MAC0332-MAC5783/entregas/issues))
- [x] [Protótipo da interface](./entrega2-anexos/Prototipo_Telas_Questibular.pdf) da solução (média/alta fidelidade)
- [x] Definição das tecnologias que serão utilizadas:
    - **Linguagem de programação:** devido a familiaridade da equipe com .Net, a linguagem de programação para backend foi alterada para .NET ([repositório novo](https://github.com/USP-EngSoft-MAC0332-MAC5783/questibular-dotnet-api)). Frontend continua usando Javascript.
    - **Banco de dados:** PostgreSQL - banco relacional devido a familiaridade da equipe
    - Frameworks: .NET Core para backend e Vue com Bootstrap para frontend.
    - APIs: ENEM API
- [x] Definição de arquitetura inicial
    - MVC - Frontend separado de Backend e base de dados.

