## Sistema de Gerenciamento de Biblioteca - Desafio CRUD em Java com Spring Boot

Neste desafio, você será responsável por desenvolver um sistema de gerenciamento de biblioteca utilizando Java com Spring Boot. O sistema consistirá nas seguintes entidades: "Autor", "Editora" e "Livro". Abaixo, apresento a estrutura das entidades, seus atributos, relacionamentos e os requisitos de funcionalidades para cada uma delas:

### Entidade: Autor

|Atributo	|Tipo	|Descrição|
|--|--|--|
|id|	Long|	Identificador único|
|nome|	String|	Nome do autor|
|dataNascimento|	LocalDate|	Data de nascimento do autor|
|nacionalidade|	String|	Nacionalidade do autor|



<br></br>

**Requisitos de Funcionalidades para a Entidade Autor:**

-   Cadastrar um novo autor com nome, data de nascimento e nacionalidade.
-   Listar todos os autores cadastrados.
-   Visualizar os detalhes de um autor específico.
-   Atualizar informações de um autor.
-   Excluir um autor.

### Entidade: Editora


|Atributo	|Tipo	|Descrição|
|--|--|--|
|id|	Long|	Identificador único|
|nome|	String|	Nome da editora|
|endereco|	String|	Endereço da editora|
|telefone|	String|	Número de telefone|


<br></br>
**Requisitos de Funcionalidades para a Entidade Editora:**

-   Cadastrar uma nova editora com nome, endereço e telefone.
-   Listar todas as editoras cadastradas.
-   Visualizar os detalhes de uma editora específica.
-   Atualizar informações de uma editora.
-   Excluir uma editora.

### Entidade: Livro


|Atributo	|Tipo	|Descrição|
|--|--|--|
|id|	Long|	Identificador único|
|titulo|	String|	Título do livro|
|anoPublicacao|	Integer|	Ano de publicação do livro|
|autor|	Autor|	Autor do livro (relacionamento)|
|editora|	Editora|	Editora do livro (relacionamento)|

<br></br>
**Requisitos de Funcionalidades para a Entidade Livro:**

-   Cadastrar um novo livro com título, ano de publicação, autor e editora associados.
-   Listar todos os livros cadastrados.
-   Visualizar os detalhes de um livro específico, incluindo informações do autor e da editora.
-   Atualizar informações de um livro.
-   Excluir um livro.

**Desafios adicionais:**

-   Implementar validações adequadas para os atributos das entidades (ex: nome não pode ser vazio, ano de publicação válido, etc.).
-   Implementar relacionamentos corretos entre as entidades no banco de dados usando JPA e Hibernate.
-   Criar endpoints RESTful utilizando o Spring MVC para as operações de CRUD de cada entidade.

Lembre-se de que este desafio tem como objetivo auxiliar no desenvolvimento de suas habilidades em Java com Spring Boot. Sinta-se à vontade para personalizar e expandir o sistema de acordo com suas preferências. Desejo sucesso e aproveitamento ao desenvolver o projeto!