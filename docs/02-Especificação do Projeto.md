# Especificações do Projeto

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação de possíveis usuários em um trabalho de consulta feito pelos membros da equipe. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.

## Personas

Maria das Graças . Idade: 42 . Ocupação Professora . Aplicativos: Facebook, Instagram, Netflix, Nubank . Frustrações: Dificuldade de encontrar livros didáticos para seus alunos . Hobbies, História: Hidroginástica, Forró, Ir ao cinema . Motivações: Em busca de maior conhecimento , para expressá-los para seus alunos.

Matheus Ferreira . Idade: 27 . Ocupação: Estudante de Educação física . Aplicativos: Instagram, Linkedin, Netflix, Apostas Esportivas . Frustrações: Dificuldade para encontrar livros sobre hipertrofia . Hobbies, História: Churrasco, com os amigos, Academia, Bar com amigos . Motivações: Em busca de conhecimento para desenvolvimento próprio corporal e profissional.

Isadora Ferreira . Idade: 24 . Ocupação: Estudante de direito . Aplicativos: Instagram, STF, Itaú, Teams . Frustrações: Dificuldade para encontrar livros atualizados sobre leis e artigos , EX: valdemecum . Hobbies, História: Cinema, Viajar, Projetos sociais . Motivações: Conhecimento para sua graduação em Direito.

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
