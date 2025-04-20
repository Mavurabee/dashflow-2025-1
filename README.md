<h1 align="center">📊 🎯 YOUTAN DASH 📈 📶</h1>
<h3 align="center">Repositório dedicado ao versionamento do projeto API do 5º semestre de Banco de Dados.</h3>

---

## 🎯 Objetivo do Projeto
> [!IMPORTANT]
> O objetivo do projeto é desenvolver uma plataforma integrada a ferramenta de gestão de projetos Taiga, com o intuito de gerar e visualizar indicadores relacionados ao andamento de projetos. A plataforma deve fornecer um dashboard que permita a extração e análise de métricas importantes, como a quantidade de cards criados e finalizados em um período, tempo médio de execução de cards, distribuição de cards por colaborador, e outros indicadores relevantes para a gestão de projetos. A plataforma deve oferecer diferentes níveis de acesso para usuários, como Operador, Gestor e Admin, garantindo que cada perfil tenha acesso apenas às informações pertinentes ao seu papel. O projeto visa facilitar a visualização e o monitoramento do progresso dos projetos, tornando o processo mais eficiente, transparente e acessível para todos os envolvidos.

---

# 🔍 Tópicos
- <a href="#documentacoes">📚 Documentações</a>
- <a href="#tecnologias">🔌 Tecnologias</a>
- <a href="#requisitos">📋 Requisitos</a>
- <a href="#backlog">📈 Product Backlog</a>
- <a href="#sprint-backlog">🔄 Sprint Backlog</a>
- <a href="#membros">👥 Membros</a>

---

## 📚 Documentações <a id="documentacoes"></a>

> [!NOTE]
> Documentações e guias do projeto:

- [Documentação de Produto](./product-documentation-2025-1)
- [Deploy Automático](https://github.com/manolito-fatec/dashflow-2025-1/wiki/Deploy-Autom%C3%A1tico)
- [Integração Contínua (CI)](https://github.com/manolito-fatec/dashflow-2025-1/wiki/Integra%C3%A7%C3%A3o-Cont%C3%ADnua-(CI))
- [Padrão de Projeto](https://github.com/manolito-fatec/dashflow-2025-1/wiki/Padr%C3%A3o-de-Projeto)
- [Padrão para Documentação](https://github.com/manolito-fatec/dashflow-2025-1/wiki/Padr%C3%A3o-para-Documenta%C3%A7%C3%A3o)
- [Testes](https://github.com/manolito-fatec/dashflow-2025-1/wiki/Testes)
- [Wireframe - Figma](https://www.figma.com/design/36kM1fJx7vGObzNir5PiL5/Logo?node-id=0-1&t=PsfYpFcVNKDPOzwy-1)
---

## 🔌Tecnologias <a id="tecnologias"></a>
> [!NOTE]
> Tecnologias utilizadas no desenvolvimento do projeto:

<h4 align="left">
<a href="https://spring.io/projects/spring-boot" target="_blank"><img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"></a>
<a href="https://spring.io/projects/spring-security" target="_blank"><img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Security"></a>
<a href="https://github.com/features/actions" target="_blank"><img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"></a>
<a href="https://swagger.io/" target="_blank"><img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white" alt="Swagger"></a>
<a href="https://jwt.io/" target="_blank"><img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT"></a>
<a href="https://junit.org/" target="_blank"><img src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit"></a>
<a href="https://vuejs.org/" target="_blank"><img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js"></a>
<a href="https://www.primefaces.org/primevue/" target="_blank"><img src="https://img.shields.io/badge/PrimeVue-4CAF50?style=for-the-badge&logo=vue.js&logoColor=white" alt="PrimeVue"></a>
<a href="https://axios-http.com/" target="_blank"><img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios"></a>
<a href="https://www.figma.com/" target="_blank"><img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"></a>
<a href="https://vitest.dev/" target="_blank"><img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest"></a>
<a href="https://www.postgresql.org/" target="_blank"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"></a>
<a href="https://yarnpkg.com/" target="_blank"><img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white" alt="Yarn"></a>
<a href="https://www.npmjs.com/" target="_blank"><img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"></a>
</h4>

---

<br>

## 📋 Requisitos <a id="requisitos"></a>

<a href="https://youtan-req.vercel.app/#Introduction">💻 Requisitos page</a>

### 📌 Requisitos Não Funcionais
| **ID** | **Título** |
| :-------------: | :------------- |
|RNF01| Documentação API – Application Programming Interface |
|RNF02| Responsivo |
|RNF03| Manual do Usuário |
|RNF04| Modelagem do Banco de Dados |
|RNF05| Implementação da pipeline de DevOps.|
---

### 📌 Requisitos Funcionais
| **ID** | **Persona** | **Título** | **Descrição** |
| -------------: | :-------------: | ------------- |------------- |
|R1|Operador|Total de cards|O sistema deverá apresentar um componente visual, denominado "card", que terá como objetivo exibir a quantidade total de cards nos quais o operador autenticado no sistema está vinculado como participante.|
|R2|Operador|Cards criados e finalizados em um período|O sistema deverá apresentar um componente visual em formato de gráfico que demonstre a quantidade de cards criados e a quantidade de cards finalizados dentro de um período de tempo selecionável.|
|R3|Operador|Total de cards por status do projeto|O sistema deverá apresentar um componente visual em formato de gráfico que demonstre a quantidade de cards em cada um dos seguintes status dentro de um projeto específico: New, In Progress, Ready for Test, Closed e Needs Info. Este gráfico tem como objetivo fornecer uma visão clara da distribuição dos cards ao longo do fluxo de trabalho do projeto.|
|R4|Operador|Tempo médio de conclusão de um card|O sistema deverá apresentar um componente visual, denominado "card", que terá como objetivo exibir o tempo médio de finalização dos cards.|
|R5|Operador|Total de projetos|O sistema deverá apresentar um componente visual, denominado "card", que terá como objetivo exibir a quantidade total de projetos nos quais o operador autenticado no sistema está vinculado como participante.|
|R6|Operador|Informações sobre o perfil do operador|O sistema deverá apresentar ao operador autenticado na interface informações relevantes sobre sua conta, username, email e role.|
|R7|Operador|Realizar login na aplicação|O sistema deve garantir que o operador seja designado para a função ROLE_USER, assegurando que ele tenha acesso e permissões adequadas para visualizar e interagir apenas com as informações que são exclusivamente suas.|
|R8|Gestor|Quantidade de cards por operador sob gestão do gestor|O sistema deverá apresentar um componente visual ("card") que exiba, para o gestor autenticado, a quantidade total de cards associados a cada um dos operadores sob sua gestão. Este card permitirá ao gestor ter uma visão geral da distribuição de cards entre sua equipe.|
|R9|Gestor|Total de cards atribuídos ao gestor|O sistema deverá apresentar um componente visual ("card") que exiba, para o gestor autenticado, a quantidade total de cards que foram especificamente atribuídos a ele como responsável ou participante.|
|R10|Gestor|Tempo médio de finalização dos cards dos operadores sob gestão do gestor|O sistema deverá apresentar um componente visual ("card") que exiba, para o gestor autenticado, o tempo médio de finalização dos cards concluídos por todos os operadores por semana.|
|R11|Gestor|Quantidade de cards que passaram por retrabalho|O sistema deverá apresentar um componente visual ("card") que exiba, para o gestor autenticado, a quantidade de cards que foram identificados como tendo passado por retrabalho.|
|R12|Gestor|Total de cards por status nos projetos|O sistema deverá apresentar um componente visual em formato de gráfico de pizza que demonstre a quantidade de cards em cada um dos seguintes status dentro dos projetos: New, In Progress, Ready for Test, Closed e Needs Info. Este gráfico tem como objetivo fornecer uma visão clara da distribuição dos cards ao longo do fluxo de trabalho do projeto.|
|R13|Gestor|Quantidade de tipos de Issues nos projetos|O sistema deverá apresentar um componente visual em formato de gráfico que exiba a quantidade de issues, agrupadas por projeto, prioridade e tipo (Bug, Enhancement, Question).|
|R14|Gestor|Cards criados e finalizados dentro de um período|O sistema deverá apresentar um componente visual em formato de gráfico que exiba a quantidade de cards criados e a quantidade de cards finalizados dentro de um período de tempo selecionável pelo gestor.|
|R15|Gestor|Quantidade de tags no projeto|O sistema deverá apresentar um componente visual em formato de gráfico que exiba a quantidade de cada tipo de tag utilizada em cada projeto.|
|R16|Gestor|Perfil do gestor|O sistema deverá apresentar ao gestor autenticado na interface informações relevantes sobre sua conta,foto,username,email e role.|
|R17|Gestor|Fazer login na aplicação|O sistema deve garantir que o gestor seja designado para a função ROLE_MANAGER, assegurando que ele tenha acesso e permissões adequadas para visualizar e gerenciar informações pertinentes aos projetos sob sua responsabilidade, bem como seus próprios dados, e cards dos operadores.|
|R18|Admin|Total de Projetos|O sistema deverá apresentar um componente visual ("card") que exiba, a quantidade de projetos que o admin administra.|
|R19|Admin|Total de Cards|O sistema deverá apresentar um componente visual("card")que exiba, a quantidade de cards por projeto.|
|R20|Admin|Total de Issues|O sistema deverá apresentar um componente visual("card")que exiba, a quantidade de issues por projeto.|
|R21|Admin|Gestor de cada projeto|O sistema deverá apresentar um componente de tabela para exibir a o projeto, gestor e a quantidade de operadores.|
|R22|Admin|Cadastrar usuário|O sistema deverá permitir o cadastro de novos usuários com perfis de administrador, gestor e operador. O cadastro exigirá nome completo, e-mail único e senha. além da seleção das Roles.  Obrigatoriamente é necessário selecionar pelo menos uma ferramenta ETL de uma lista disponível.Taiga,Jira ou Trello.|
|R23|Admin|Criar uma api para integração com outro sistema(trello, Jira)|O sistema deve disponibilizar uma API (Application Programming Interface) para integração com sistemas externos, como Trello e Jira, permitindo a sincronização de dados, como cards, projetos, tarefas e indicadores, entre as plataformas.|
|R24|Admin|Exportar dados para CSV|O sistema deverá permitir que o administrador exporte seus dados para um arquivo CSV através de um botão na interface do DashBoard.|
|R25|Admin|Realizar o Login na aplicação|O sistema deve garantir que o administrador seja designado para a função ROLE_ADMIN, permitindo-lhe acessar e gerenciar informações relacionadas a todos os projetos, usuários e configurações do sistema.|
|R26|Admin|Tabela log para gestão na aplicação|Para garantir a rastreabilidade e auditoria, o sistema deverá apresentar ao administrador uma tabela detalhada de todas as ações executadas na aplicação.|
|R27|Admin|Cards criados e finalizados dentro de um período|O sistema deverá apresentar um componente visual em formato de gráfico que exiba a quantidade de cards criados e a quantidade de cards finalizados dentro de um período de tempo selecionável pelo admin.|
|R28|Admin|Perfil de Admin|O sistema deverá apresentar ao admin autenticado na interface informações relevantes sobre sua conta,foto,username,email e role.|

---

<br>


## 📈 Product Backlog <a id="backlog"></a>

|🗃️ Id| 🏅 Rank| 🔥 Prioridade| 📝 User Story| 🚀 Sprint| 🎯 Requisito do Parceiro|
 :--------: | :--------: | :--------: | -------- | :--------: | :--------: |
|US01|1|Alta|Eu, como operador, desejo visualizar a quantidade de cards atribuídos a mim e filtrar os cards dos meus projetos com base no período de criação e finalização, para acompanhar meu progresso e gerenciar melhor minhas tarefas.|1|R1,R2,RNF02,RNF04,RNF05|
|US02|2|Alta|Eu, como operador, desejo visualizar todos os cards com base em seu status para acompanhar o andamento das tarefas nos projetos.|1|R3,RNF01,RNF02,RNF03,RNF05|
|US03|3|Alta|Eu, como operador, desejo visualizar o tempo médio de conclusão dos cards finalizados e a quantidade de projetos em que estou participando para acompanhar meu desempenho e a eficiência na conclusão das tarefas.|1|R4,R5,RNF01,RNF02,RNF03,RNF05|
|US04|4|Alta|Eu, como gestor, desejo visualizar a quantidade de cards atribuídos a cada operador sob minha gestão, assim como os cards designados a mim, para monitorar a distribuição de tarefas e gerenciar melhor a equipe.|2|R8,R9,RNF01,RNF02,RNF03,RNF05|
|US05|5|Alta|Eu, como gestor, desejo filtrar os cards dos projetos que gerencio e que estão atribuídos a mim, considerando um período específico, para acompanhar a evolução das tarefas e a finalização das atividades.|2|R14,RNF01,RNF02,RNF03,RNF05|
|US06|6|Alta|Eu, como gestor, desejo visualizar todos os cards dos operadores que gerencio, filtrando-os com base em seu status, para monitorar o andamento das tarefas e a progressão dos projetos.|2|R12,RNF01,RNF02,RNF03,RNF05|
|US07|7|Alta|Eu, como gestor, desejo visualizar informações por meio de indicadores que destaquem o tempo médio de conclusão dos cards finalizados pela equipe. Quero acompanhar o tempo médio que cada operador da equipe leva para finalizar uma tarefa, para avaliar a produtividade individual e coletiva.|2|R10,RNF01,RNF02,RNF03,RNF05|
|US08|8|Alta|Eu, como gestor, desejo visualizar informações sobre retrabalhos e também obter detalhes sobre as issues dos projetos, incluindo a quantidade total, tipo, gravidade e prioridade, para analisar a eficiência da equipe e priorizar as ações corretivas de forma adequada.|2|R11,R13,RNF01,RNF02,RNF05|
|US09|9|Alta|Eu,como gestor de projetos, quero visualizar o total de cards organizados por tags, para poder analisar rapidamente a distribuição das tarefas e acompanhar o progresso de cada área do projeto de forma mais eficiente.|2|R15,RNF01,RNF02,RNF03,RNF05|
|US10|10|Media|Eu, como operador, gestor ou admin, desejo fazer authenticação na aplicação para acessar meus indicadores, para monitorar o desempenho e os dados relevantes.|2|R6,R7,R16,R17,R25,R28,RNF01,RNF02,RNF03,RNF05|
US11|11|Media|Eu, como admin, desejo realizar o cadastro de novos usuários, sendo obrigatório associar ao menos uma ferramenta de gestão de projetos (Taiga, Trello ou Jira) durante o processo de criação da conta, para fins de integração e rastreamento das atividades no pipeline de ETL.|3|R22,RNF01,RNF02,RNF03,RNF05|
|US12|12|Media|Eu, como admin, desejo visualizar informações sobre a quantidade de projetos e o número de cards em cada projeto, para ter uma visão abrangente do andamento e da gestão dos projetos.|3|R18,R19,RNF01,RNF02,RNF03,RNF05|
|US13|13|Media|Eu, como admin, desejo visualizar a quantidade de cards criados e finalizados dentro de um período específico, para monitorar o progresso das tarefas.|3|R27,RNF01,RNF02,RNF03,RNF05|
|US14|14|Media|Eu, como admin, desejo visualizar uma tabela que liste cada projeto, o gestor responsável e o número de pessoas alocadas em cada um, a fim de ter uma visão clara da estrutura e alocação de recursos nos projetos.|3|R21,RNF01,RNF02,RNF03,RNF05|
|US15|15|Media|Eu, como administrador, desejo visualizar, para cada projeto, detalhes sobre as issues dos projetos, incluindo a quantidade total, tipo, gravidade e prioridade, para analisar a eficiência da equipe e priorizar as ações corretivas de forma adequada.|3|R20,RNF01,RNF02,RNF03,RNF05|
|US16|16|Baixa|Eu, como admin, desejo integrar novas ferramentas ao sistema, permitindo a ampliação das funcionalidades e a interoperabilidade com diferentes plataformas, a fim de melhorar a eficiência e a experiência dos usuários.|3|R23,RNF01,RNF02,RNF03,RNF05|
|US17|17|Baixa|Eu, como admin, quero realizar a exportação dos dados do Dashboard para um arquivo CSV, para que eu possa analisar, compartilhar ou arquivar os dados de forma prática e organizada, fora da plataforma.|3|R24,RNF01,RNF02,RNF03,RNF05|
|US18|18|Baixa|Eu, como admin, para fins de auditoria e acompanhamento,  desejo visualizar uma tabela abrangente que registre cada ação realizada na aplicação, incluindo detalhes como o usuário que a executou, o tipo de ação e o timestamp da ocorrência.|3|R26,RNF01,RNF02,RNF03,RNF05|

---

<br>

## 🔄 Sprint Backlog <a id="sprint-backlog"></a>

## Sprint 1️⃣

| 🗃️ User Story ID | 🚨 Estimativa |
| :-------------: | :-------------: |
|US01|18
|US02|11
|US03|28

## Sprint 2️⃣

| 🗃️ User Story ID | 🚨 Estimativa |
| :-------------: | :-------------: |
|US04|08|
|US05|05|
|US06|20|
|US07|10|
|US08|20|
|US09|10|
|US10|13|

## Sprint 3️⃣

| 🗃️ User Story ID | 🚨 Estimativa |
| :-------------: | :-------------: |
|US11|A determinar|
|US12|A determinar|
|US13|A determinar|
|US14|A determinar|
|US15|A determinar|
|US16|A determinar|
|US17|A determinar|
|US18|A determinar|

---

<br>

## 👥 Team Members <a id="membros"></a>
|Nome|Função|LinkedIn|  
| -------- | -------- | -------- |
|**Paulo Arantes Machado**|Product Owner|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/paulo-antonio-arantes-machado-a8a89b23b)|
|**Otavio Calderan Bruguel**|Scrum Master|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/otavio-calderan-578b48239)|
|**André Hideaki Wakugawa**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/andrewakugawa/)|
|**Beatriz Bonatto**|Desenvolvedora|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://br.linkedin.com/in/beatriz-bonatto-263530156)|
|**Cauê Vieira da Silva**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/cau%C3%AA-vieira-ba62b4244/)|
|**Gabriel Bartolomeu Guska**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/gabiel-guska-5860a1271/)|
