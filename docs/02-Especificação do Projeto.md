# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação de possíveis usuários em um trabalho de consulta feito pelos membros da equipe. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas na Figuras que se seguem.


|Nome: Maria das Graças             |Idade: 42 anos               |Ocupação: Professora          | 
|------------------------------------------------------------------------------------------------|
|Motivações: Em busca de maior conhecimento para expressá-los para seus alunos                   |
|Frustaçoes: Dificuldade de encontrar livros didaticos para seus alunos                          |
|Aplicativos:Facebook, Instagram, Netflix e Nubank                                               |
|Hobbies: Hidroginastica, Forro e Cinema                                                         |
|------------------------------------------------------------------------------------------------|
|Nome: Maria das Graças             |Idade: 42 anos               |Ocupação: Professora          | 
|------------------------------------------------------------------------------------------------|
|Motivações: Em busca de maior conhecimento para expressá-los para seus alunos                   |
|Frustaçoes: Dificuldade de encontrar livros didaticos para seus alunos                          |
|Aplicativos:Facebook, Instagram, Netflix e Nubank                                               |
|Hobbies: Hidroginastica, Forro e Cinema                                                         |
|------------------------------------------------------------------------------------------------|
|Nome: Maria das Graças             |Idade: 42 anos               |Ocupação: Professora          | 
|------------------------------------------------------------------------------------------------|
|Motivações: Em busca de maior conhecimento para expressá-los para seus alunos                   |
|Frustaçoes: Dificuldade de encontrar livros didaticos para seus alunos                          |
|Aplicativos:Facebook, Instagram, Netflix e Nubank                                               |
|Hobbies: Hidroginastica, Forro e Cinema                                                         |
|------------------------------------------------------------------------------------------------|


## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Matheus Ferreira    | Fazer consultas rápidas            | Agilidade na busca de conteúdo         |
|Maria das Graças    | Ter fácil acesso                   | Aplicação simples e intuitivo          |
|Isadora Ferreira    | Verificar a disponibilidades       | Fazer pesquisa de obras literárias     |
|Matheus Ferreira    | Facilidade de reservas             | Ter uma opção de reservas online       |
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

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| A solução deverá ser entregue ao fim do semestre letivo, não podendo extrapolar a data de 19/06/2023. |
|RE-02| A equipe não poderá subcontratar o desenvolvimento do sistema.        |
|RE-02| O sistema deverá ser  interativo.  |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
