🍤 Sistema de Banco de Dados – Restaurante Le Guste

Este repositório contém o desenvolvimento completo do banco de dados do restaurante fictício Le Guste, criado para a disciplina de Banco de Dados.
O objetivo é implementar um modelo relacional funcional em SQLite, manipular dados utilizando SQL e demonstrar o ciclo completo de criação, inserção, consulta e manutenção da base.

📌 1. Objetivos do Projeto

Construir as tabelas do banco de dados com base no modelo lógico.

Inserir dados reais e coerentes com o minimundo definido.

Realizar consultas SQL com JOIN, WHERE, ORDER BY, LIMIT e agregações.

Manipular dados utilizando UPDATE e DELETE.

Garantir integridade via chaves primárias e estrangeiras.

Versionar o projeto utilizando Git e disponibilizá-lo publicamente no GitHub.

📌 2. Ambiente Utilizado

SGBD: SQLite

Ferramenta: SQLiteStudio

Linguagem: SQL (DML e DDL)

Versionamento: Git & GitHub

📁 3. Estrutura do Repositório
bd-le-guste/
│
├── /scripts/
│   ├── 01_create_tables.sql       → Criação das tabelas e relacionamentos
│   ├── 02_insert_dados.sql        → População das tabelas
│   ├── 03_select_consultas.sql    → Consultas SELECT variadas
│   ├── 04_update.sql              → Comandos de atualização (UPDATE)
│   ├── 05_delete.sql              → Comandos de exclusão (DELETE)
│
└── README.md

🍽️ 4. Modelo Lógico – Visão Geral

Entidades principais:

Mesa – mesas do restaurante

Pedido – pedidos vinculados às mesas

ItemPedido – itens que compõem cada pedido

Prato – pratos do cardápio

Pagamento – pagamento final de cada pedido

Relacionamentos e cardinalidades:

Mesa 1 → N Pedido

Pedido 1 → N ItemPedido

Prato 1 → N ItemPedido

Pedido 1 → 1 Pagamento

⚙️ 5. Como Executar o Projeto
Passo 1 – Instale o SQLiteStudio

Baixe em: https://sqlitestudio.pl

Passo 2 – Crie o banco

Abra o SQLiteStudio

Clique em “Create a new database”

Nomeie como le_guste.db

Passo 3 – Execute os scripts na ordem correta

01_create_tables.sql

02_insert_dados.sql

03_select_consultas.sql

04_update.sql

05_delete.sql

📊 6. Scripts Disponíveis
✔️ Criação das Tabelas (DDL)

Define tabelas, chaves estrangeiras e estrutura do banco.

✔️ Inserção de Dados (DML – INSERT)

Popula as tabelas Mesa, Pedido, Prato, ItemPedido e Pagamento.

✔️ Consultas (DML – SELECT)

Inclui consultas simples, intermediárias e avançadas.

✔️ Manipulação de Dados (DML – UPDATE / DELETE)

Exemplos reais de alteração e remoção utilizando condições.

🧠 7. Aprendizados Desenvolvidos

Uso prático da linguagem SQL.

Manipulação de banco de dados relacional.

Estruturação de scripts organizados por função.

Aplicação de conceitos de normalização, integridade e relacionamentos.

Versionamento de código com Git e GitHub.

🤝 8. Autor

Jean Nathannael Martins Brito
📚 Disciplina: Banco de Dados
💾 Projeto acadêmico — 2025
