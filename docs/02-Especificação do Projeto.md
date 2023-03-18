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

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Matheus Ferreira    | Fazer consultas rápidas            | Agilidade na busca de conteúdo         |
|Maria das Graças    | Ter fácil acesso                   | Aplicativo simpres e intuitivo         |
|Isadora Ferreira    | Verificar a disponibilidades       | Fazer pesquisa de obras literárias     |
|Matheus Ferreira    | Reservas de livros                 | Ter uma opção de reservas online       |
|Maria das Graças    | Renovação de emprestimos           | Ter a opcao de fazer renovações online |
|Isadora Ferreira    | contato com a biblioteca           | Canal com administrador da biblioteca  |


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

![Diagrama](/docs/img/Gest%C3%A3o%20de%20Bibliotecas.png)

### CRUD - Usuários

Create - O usuário insere as seguintes informações para criar um novo usuário: Nome completo, data de nascimento, e-mail, telefone e endereço.

Read - O usuário seleciona um usuário a partir de uma lista e o sistema exibe as informações do usuário: Nome completo, data de nascimento, e-mail, telefone, endereço e histórico de empréstimos e devoluções.

Update - O usuário seleciona um usuário a partir de uma lista e pode atualizar as seguintes informações: Nome completo, data de nascimento, e-mail, telefone e endereço.

Delete - O usuário seleciona um usuário a partir de uma lista e pode excluí-lo do sistema.

### CRUD - Livros

Create - A criação do cadastro de um novo livro pode ser realizada através de um formulário: O bibliotecário deve informar os dados do livro, como título, autor e ISBN.

Read - A leitura de informações sobre um livro pode ser realizada de diversas formas: O bibliotecário pode pesquisar o livro pelo título, autor ou ISBN. Também pode ser possível visualizar uma lista completa de todos os livros cadastrados na biblioteca. Ao selecionar um livro, o sistema deve exibir as informações completas, incluindo disponibilidade, localização, número de exemplares, empréstimos e histórico.

Update - A atualização de informações de um livro pode ser realizada pelo bibliotecário: O bibliotecário pode editar informações básicas, como título, autor e ISBN. O sistema pode permitir que o bibliotecário adicione ou remova exemplares, atualize o estado de disponibilidade, informe a localização ou altere as informações de empréstimo.

Delete - A exclusão de um livro pode ser realizada pelo bibliotecário: O bibliotecário ao excluir um livro, o sistema deve remover todas as informações relacionadas, incluindo exemplares, empréstimos e histórico.

### Lógica de negócio

Criação de usuários:

⦁	A tela de criação de usuários deve permitir a inserção de informações como nome, endereço, telefone e e-mail do usuário.

⦁	O sistema deve validar se todas as informações obrigatórias foram preenchidas antes de permitir que o usuário seja criado.

Empréstimo de livros:

⦁	O sistema deve permitir que os usuários pesquisem livros no sistema e selecionem os livros que desejam pegar emprestado.

⦁	O sistema deve verificar se os livros estão disponíveis para empréstimo antes de permitir que os usuários realizem a operação.

⦁	O sistema deve registrar a data de empréstimo e a data de devolução esperada para cada livro emprestado.

⦁	O sistema deve permitir que os usuários peguem emprestado mais de um livro ao mesmo tempo.

Devolução de livros:

⦁	O sistema deve permitir que os usuários pesquisem livros emprestados no sistema e selecionem os livros que desejam devolver.

⦁	O sistema deve permitir que os usuários devolvam mais de um livro ao mesmo tempo.

Visualização de histórico de empréstimos:

⦁	O sistema deve permitir que os usuários visualizem o histórico de empréstimos de cada livro.
⦁	O sistema deve exibir informações como a data de empréstimo, data de devolução.
Visualização de livros emprestados:

⦁	O sistema deve permitir que os funcionários da biblioteca visualizem a lista de livros atualmente emprestados e seus respectivos usuários.

⦁	O sistema deve permitir que os funcionários da biblioteca gerenciem empréstimos em caso de atraso ou de falta de devolução de livros.

### Relatórios

Livros mais reservados por período 

Este relatório pode incluir informações sobre os livros mais populares em um determinado período, como semana, mês ou ano, o número de empréstimos realizados para cada livro e outras informações relevantes. Com esses dados, o bibliotecário pode ter uma visão geral dos livros mais populares na biblioteca e planejar aquisições e estratégias de gestão de coleção de forma mais eficiente.

Usuários que mais reservaram livros por período

Este relatório pode apresentar informações sobre os usuários que mais realizaram reservas no período escolhido, como semana, mês ou ano. O relatório pode incluir detalhes sobre o número de reservas realizadas por cada usuário, e o número de empréstimos realizados. Com esses dados, o bibliotecário pode identificar os usuários mais ativos na biblioteca e personalizar sua estratégia de atendimento e comunicação com esses usuários.
