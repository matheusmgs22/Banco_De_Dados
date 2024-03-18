# Banco_De_Dados
Primeiro projeto de Banco de Dados 1 

O Objetivo é desenvolver um sistema de gerenciamento de biblioteca utilizando o Modelo Entidade-Relacionamento (MER).

Sistema de Gerenciamento de Biblioteca
Aluno: Matheus Garcia da Silva.

As entidades principais escolhidas foram: Livro, Autor, Usuário (Cliente), Empréstimo e Funcionário.


A primeira entidade é o livro. Que tem como atributos, os seguintes itens: ID_livro, autor, título, Gênero, número de páginas e Sessão. O livro tem como atributo identificador, seu ID_livro e título, onde essas informações serão utilizadas para encontrar um livro específico na biblioteca e sua sessão (local onde o livro se encontra na biblioteca). Pesquisar o livro a partir do seu ID, resolve problemas como; Livro do mesmo autor e mesmo título de anos diferentes, ou de línguas diferentes, ou de edições diferentes. 

A segunda entidade é o autor. Que tem como atributos, os seguintes itens: Nome, Gênero literário, Data de nascimento, nacionalidade. Ele tem como atributos principais seu nome e data de nascimento, que tem como função facilitar o cliente ou o próprio bibliotecário a encontrar diversas obras de um único autor. O autor tem um relacionamento com a entidade livro, já que o autor que escreve os livros. 
A terceira entidade principal é o Usuário (cliente). Que tem como atributos, os seguintes itens: ID_usuario, nome, e-mail, telefone, endereço, data nascimento, cpf. Ele tem como atributo principal seu CPF e o ID_usuario, que servem para diferenciar cada usuário. Pode acontecer de um usuário ter o mesmo nome e nascer no mesmo dia que o outro, nunca se sabe. Com o ID do usuário e seu CPF, o próprio sistema da biblioteca identifica um usuário cadastrado e já puxa o histórico de empréstimos e as datas de devoluções dos próximos livros. 

Essa entidade, tem uma ligação importante com a entidade empréstimo, que é a quarta entidade principal. Que tem como atributos, os seguintes itens: ID_livro, ID_Emprestimo, ID_usuario, Data_de_devolução, Disponibilidade. Ele tem como identificadores o ID_livro, ID_Emprestimo, ID_usuario, onde tem como objetivo facilitar a busca de um livro através. O usuário pode efetuar um empréstimo de um livro, de forma digital – usando o aplicativo ou site da biblioteca – ou de forma presencial na própria biblioteca. Se ele efetuar o empréstimo de forma digital, o livro é entregue através de um motoboy em sua residência, tudo controlado pelo seu smartphone. Ele pode até mesmo pagar o empréstimo do livro, o frete, aumentar a data de devolução, ver as disponibilidades dos livros e até solicitar a devolução do livro, de forma digital em nosso app. 

E a última entidade principal é o funcionário. Que tem como atributos, os seguintes itens: ID_funcionario, nome, CPF, data_nascimento. Essa entidade se relaciona com a entidade Departamentos, onde cada funcionário faz parte de um departamento da biblioteca. O mais importante, além dos bibliotecários, é a parte administrativa. Que faz parte da entidade departamento, mas ela manda nos demais departamentos da biblioteca. É nessa entidade que temos o gerente, que é responsável por toda a biblioteca. Em departamentos, temos as entidades manutenção (para limpeza e manutenção), vigilância (para segurança) e os bibliotecários. Os bibliotecários são responsáveis por todos os livros da biblioteca, e eles que cuidam da parte de empréstimo de livros. Além também, de entrar em contato com a entidade Editora para comprar livros novos. 
Por fim, temos algumas entidades que servem para o lazer do cliente enquanto lê um bom livro na biblioteca. As entidades cafeteria e Lojinha, tem seus próprios produtos e funcionários. E tem como objetivo trazer mais recursos financeiros para a biblioteca. 



![1_Projeto_Banco_de_dados_concluido](https://github.com/matheusmgs22/Banco_De_Dados/assets/101107346/07523b64-e6b8-4062-bb26-7fddc226d492)



![IMG_0308](https://github.com/matheusmgs22/Banco_De_Dados/assets/101107346/dbbad4a5-1dc1-4de9-b03a-ed6745b87f68)

