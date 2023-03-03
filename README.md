# Projeto - Criando uma API no visual Studio
## ✨ _API catálogo_✨

Uma web API que serve para criar catálogos de produtos em cada tipo de categoria, que poderá atender a uma rede de lojas, supermercados e também consumidores finais. 



## Features

- Um serviço RESTful que permite que aplicativos clientes acessem e gerenciem um ocatálogo de produtos e categorias.
- Abordado os conceitos fundamentais da criação de uma Web API usando o ASP NET core / EntityFramework Core.
- Expor endpoints para criar, ler, editar e excluir produtos/categorias e também consultar produtos/categorias usando os verbos HTTP e os códigos de status.


## Roteiro da criação da Web Api

* Criar o modelo de entidades – Produtos e Categoria.
* Configurar o projeto para usar o EF Core e incluir referências ao EF Core.
* Definir o banco de dados usado – MySql.
* Definir a classe de contexto do EF core – AppDbContext.
* Definir o mapeamento de entidades para as tabelas – DbSet<T>.
* Registrar o contexto como um serviço – Program.
* Definir a string de conexão no arquivo appsettings.json.
* Definir o provedor do banco de dados (Pomelo) e obter a string de conexão.
* Aplicar o Migrations e criar o banco de dados e as tabelas.
* Criar os controladores: ProdutosController e CategoriasController.
* Definir os endpoint ou métodos Action para realizar as operações CRUD.





