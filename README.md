# Orgs-Listagem-de-Produtos-Kotlin
 Aplicativo Android com Kotlin para Cadastro, Listagem, Exclusão com Room

✔️Técnicas e tecnologias utilizadas: 

**Jetpack Room:** lib para persistência de dados em banco de dados interno com SQLite

**Entidade: **definição da tabela que será criada no banco de dados

**DAO:** definição dos comportamentos com o banco de dados
comportamentos definidos : inserir, alterar, remover e consultar de todos os registros e com filtro

**Database:** configuração para criar a conexão com o banco de dados
conversor de tipo: converter um tipo complexo para um tipo compatível com o **SQLite**

**Menu de opções:** menu para editar e remover
Extras: técnica para enviar e receber informações entre Atividades
inicialização lateinit e lazy: técnicas para criar propriedades em Activities que não podem ser inicializadas na construção da Activity
