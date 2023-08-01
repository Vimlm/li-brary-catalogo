# Li Brary Catalogação

## Descrição do Projeto
Este projeto consiste em uma aplicação de catalogação de uma biblioteca, onde serão armazenadas informações sobre endereços, pessoas, funcionários, autores, editoras e livros. O objetivo é criar um sistema que permita gerenciar de forma eficiente o acervo da biblioteca e facilitar a busca e organização das informações.

## Visualizar o diagrama do projeto no DBDiagram
- Clicando [aqui](https://dbdiagram.io/d/64c5584c02bd1c4a5ee8de0d) você consegue ver ele online;

## Tabelas do Banco de Dados
### Tabela: Endereços
- Armazena informações sobre os endereços de pessoas, funcionários e editoras.

### Tabela: Pessoas
- Contém informações sobre as pessoas cadastradas na biblioteca, incluindo leitores e clientes em geral.

### Tabela: Funcionários
- Armazena informações sobre os funcionários que trabalham na biblioteca.

### Tabela: Autores
- Contém informações sobre os autores das obras presentes na biblioteca.

### Tabela: Editoras
- Armazena informações sobre as editoras responsáveis pelas publicações disponíveis na biblioteca.

### Tabela: Livros
- Contém informações sobre os livros disponíveis na biblioteca.

## Como usar
Para utilizar a aplicação, primeiro, é necessário criar um banco de dados, você deve clonar o repositório e abrir o seu MySQLWorkbanch.  
Ao abrir você deve importar os 3 scripts que tem no repositório na pasta ./scripts, depois de importar os 3 scripts você deve executar os scripts.    
A ordem de execução dos scripts é:  
- ***1º li-brary-estrutura.sql***  
para a criação do banco de dados.  
- ***2º li-brary-registros***  
Para inserir os dados dos endereços, pessoas, funcionários, autores, editoras e livros utilizando comandos SQL de inserção.  
- ***3ºli-brary-pesquisas***  
Para fazer pesquisas no banco de dados de acordo com a sua necessidade.

A partir daí, é possível realizar consultas e operações na base de dados para gerenciar o acervo da biblioteca, fazer buscas por livros, autores, editoras, entre outras funcionalidades.

## Estrutura do Projeto
📂 li-brary-catalogo  
 ┣ 📂 model    
 ┃ ┣ 📜 li-brary-diagrama.png  
 ┣ 📂 scripts    
 ┣ ┣  📜 li-brary-estrutura.sql  
 ┣ ┣  📜 li-brary-registros.sql  
 ┃ ┗  📜 li-brary-pesquisas.sql  

## Conclusão
O projeto de catalogação da biblioteca com o modelo de dados proposto visa oferecer uma solução eficiente e organizada para gerenciar o acervo de livros, os dados dos autores, das editoras, dos funcionários e dos leitores. Através dessa aplicação, é possível manter um registro detalhado das informações essenciais para a operação da biblioteca, facilitando a busca por livros, a administração dos funcionários e o acompanhamento dos dados dos leitores.  
Em resumo, o projeto de catalogação da biblioteca com o modelo de dados proposto é uma solução robusta e versátil para a gestão do acervo e informações relacionadas, buscando oferecer uma experiência mais eficiente e satisfatória tanto para os funcionários da biblioteca quanto para os seus leitores. Com o suporte da comunidade e a dedicação dos desenvolvedores, o sistema tem o potencial de se tornar uma ferramenta indispensável para a promoção do conhecimento e da cultura através da biblioteca.
