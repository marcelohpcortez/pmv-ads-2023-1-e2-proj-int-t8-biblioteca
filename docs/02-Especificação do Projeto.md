# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01| O sistema deve permitir novos usuários se cadastrarem e efetuarem login para acessar suas funcionalidades, sejam eles do tipo leitor ou bibliotecário. | Alta |
|RF-02| O sistema deve permitir que um usuário edite suas próprias informações de usuário. | Baixa |
|RF-03| O sistema deve permitir que o usuário apague sua conta.   | Baixa |
|RF-04| O sistema deve apresentar uma lista com todos os livros disponíveis na biblioteca.   | Alta |
|RF-05| O sistema deve permitir que qualquer usuário visualize todas as informações de um livro selecionado na lista.   | Média |
|RF-06| O sistema deve permitir que um usuário reserve um livro que não esteja reservado ainda.   | Média |
|RF-07| O sistema deve permitir que usuários do tipo bibliotecário cadastrem novos livros.    | Alta |
|RF-08| O sistema deve permitir que um usuário do tipo bibliotecário atualize informações dos livros.    | Média |
|RF-09| O sistema deve permitir que um usuário do tipo bibliotecário apague livros do sistema.   | Baixa |
|RF-10| O sistema deve gerar para o bibliotecário um relatório dos livros mais reservados por período.   | Média |
|RF-11| O sistema deve gerar para o bibliotecário um relatório dos usuários que mais reservaram livros por período.   | Média |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01| O sistema deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge)  | ALTA | 
|RNF-02| O sistema deve ser responsivo, permitindo que o usuário visualize de forma adequada em dispositivos móveis. |  MÉDIA | 
|RNF-03| O sistema deve estar disponível 99% das 24 horas diárias. |  MÉDIA | 
|RNF-04| O sistema deve estar alinhado com as normas de privacidade do cliente. |  ALTA | 
|RNF-05| O sistema deverá informar ao usuário quando a mesma estiver em manutenção e/ou fora do ar. |  MÉDIA | 
|RNF-06| O sistema deverá ter uma fácil usabilidade para o usuário. |  MÉDIA | 



## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| A solução deverá ser entregue ao fim do semestre letivo, não podendo extrapolar a data de 19/06/2023. |
|RE-02| A equipe não poderá subcontratar o desenvolvimento do sistema.        |
|RE-02| O sistema deverá ser  interativo.  |




## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
