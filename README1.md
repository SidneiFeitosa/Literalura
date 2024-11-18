Índice
Introdução
Funcionalidades e Demonstração da Aplicação
Acesso ao Projeto
Tecnologias Utilizadas
Challenge ONE - LiterAlura
Neste emocionante desafio de programação, convidamos você a construir seu próprio catálogo de livros: o LiterAlura. Você aprenderá a realizar solicitações a uma API de livros, manipular dados JSON, armazená-los em um banco de dados e, por fim, a filtrar e mostrar os livros e autores de interesse.

Objetivo
Desenvolver um Catálogo de Livros que ofereça interação textual (via console) com os usuários, proporcionando no mínimo 5 opções de interação. Os livros serão buscados através de uma API específica (Gutendex).

Funcionalidades e Demonstração da Aplicação
O LiterAlura permite aos usuários interagir com um catálogo de livros através de um menu no console. As principais funcionalidades incluem:

Buscar livro pelo título: Realiza uma busca na API de livros pelo título informado.
Listar livros registrados: Exibe todos os livros armazenados no banco de dados.
Listar autores registrados: Exibe todos os autores armazenados no banco de dados.
Listar autores com seus respectivos livros: Exibe todos os autores com os livros que escreveram.
Listar autores vivos em um determinado ano: Permite buscar autores que estavam vivos em um ano específico.
Listar livros por idioma: Permite buscar livros em um idioma específico.
Exemplo de Utilização
Abaixo seguem exemplos de utilização da aplicação:

Menu Principal
1 - Buscar livro pelo titulo
2 - Listar livros registrados
3 - Listar autores registrados
4 - Listar autores registrados com seus respectivos livros
5 - Listar autores vivos em um determinado ano
6 - Listar livros em um determinado idioma
0 - Sair

Pesquisa por Livros
1 - Buscar livro pelo titulo
2 - Listar livros registrados
3 - Listar autores registrados
4 - Listar autores registrados com seus respectivos livros
5 - Listar autores vivos em um determinado ano
6 - Listar livros em um determinado idioma
0 - Sair
Insira abaixo o valor correspondente à opcao desejada
> 1
> A busca pode ser feita pelo titulo junto ao nome do autor.
> Por exemplo: machado memorias
> (Machado de Assis, Memorias Phostuma...)
> Pressione a tgecla enter (entrada) oara continuar...

Listagem de Livros Registrados
1 - Buscar livro pelo titulo
2 - Listar livros registrados
3 - Listar autores registrados
4 - Listar autores registrados com seus respectivos livros
5 - Listar autores vivos em um determinado ano
6 - Listar livros em um determinado idioma
0 - Sair
Insira abaixo o valor correspondente à opcao desejada
> 2
> Titulo: A Mao e A Luva
> Idioma: pt
> Numero de downloads: 172

Pesquisa por Ano
1 - Buscar livro pelo titulo
2 - Listar livros registrados
3 - Listar autores registrados
4 - Listar autores registrados com seus respectivos livros
5 - Listar autores vivos em um determinado ano
6 - Listar livros em um determinado idioma
0 - Sair
Insira abaixo o valor correspondente à opcao desejada
> 5
Informe o ano (por exemplo, 1889):
> 1920
Autor: Teasdale, Sara (1884-1933)
***
Titulo: Love Songs
Idioma: en
Numero de downloads:160
---
Autor: Williamson, A.M. (alice Muriel) (1869-1933)
***
Pesquisa por Idioma
1 - Buscar livro pelo titulo
2 - Listar livros registrados
3 - Listar autores registrados
4 - Listar autores registrados com seus respectivos livros
5 - Listar autores vivos em um determinado ano
6 - Listar livros em um determinado idioma
0 - Sair
Insira abaixo o valor correspondente à opcao desejada
> 6
insira os dois caracteres do idioma para realizar a buscar:
Abaixo segue uma lista de possiveis idiomas,mas sinta-se à vontade para pesquisar por outros.
es - Espanhol
en - Inglês
fr - Francês
pt - Português
> pt
Titulo: A Mao e A luva
> Idioma: pt
> Numero de Downloads: 172
---
Titulo: Memorias Posthumas de Braz Cubas
Idioma: pt 
Número de downloads: 643
---
Pressione a tecla enter (entrada) para continuar...

Tratamento de Exceção
1 - Buscar livro pelo titulo
2 - Listar livros registrados
3 - Listar autores registrados
4 - Listar autores registrados com seus respectivos livros
5 - Listar autores vivos em um determinado ano
6 - Listar livros em um determinado idioma
0 - Sair
Insira abaixo o valor correspondente à opcao desejada
> 6
insira os dois caracteres do idioma para realizar a buscar:
Abaixo segue uma lista de possiveis idiomas,mas sinta-se à vontade para pesquisar por outros.
es - Espanhol
en - Inglês
fr - Francês
pt - Português
> 12
Digite um idioma valido para a pesquisa
Pressione a tecla enter (entrada) para continuar...

Acesso ao Projeto

Para acessar o projeto, basta cloná-lo em uma máquina com o git ou baixá-lo diretamente pelo GitHub. Em seguida, execute a aplicação em uma IDE Java de sua preferência.

Configuração do Ambiente

Java 17: Certifique-se de que a versão do Java instalada seja a 17.
Dependências: As dependências do projeto estão especificadas no arquivo pom.xml caso esteja utilizando Maven.
Estrutura do Projeto

Os arquivos de código estão organizados em diretórios autoexplicativos. Valem menção:

ConsumerApi: Classe responsável por fazer requisições à API externa.
DataConverter: Classe responsável por converter os dados JSON retornados pela API.
Repositories: Interfaces para acesso ao banco de dados (AuthorRepository e BookRepository).
Tecnologias Utilizadas
Java 17
Spring Boot: Para facilitar a criação de APIs e a interação com o banco de dados.
JPA/Hibernate: Para o mapeamento objeto-relacional e manipulação dos dados.
PostgreSQL: Banco de dados para armazenamento de informações.

