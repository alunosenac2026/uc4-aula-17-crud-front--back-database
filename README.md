# uc4-aula-17-crud-front-back-database

Atividade Prática: Sistema de Controle de Veículos (CRUD)

Objetivo: Desenvolver uma aplicação web completa (Front-end + Back-end + Banco de 
Dados) aplicando as quatro operações básicas de um CRUD (Create, Read, Update, Delete), 
utilizando HTML, CSS, JavaScript, PHP e MySQL.

Cenário: Você foi contratado para desenvolver um sistema simples de gerenciamento de 
frota para uma locadora/garagem de veículos. O sistema deve permitir cadastrar novos 
carros, listar os veículos disponíveis, editar informações cadastradas e remover veículos do 
sistema.

1. Estrutura do Banco de Dados

Crie um script SQL para gerar o banco de dados e a tabela conforme as especificações 
abaixo:
• Nome do Banco de Dados: GaragemDB
• Nome da Tabela: Veiculo
• Colunas da Tabela:
• id: Inteiro, Chave Primária, Auto Incremento (INT NOT NULL AUTO_INCREMENT 
PRIMARY KEY)
• modelo: Texto até 100 caracteres (VARCHAR(100)) — Ex: Onix, Civic, Corolla
• marca: Texto até 50 caracteres (VARCHAR(50)) — Ex: Chevrolet, Honda, Toyota
• ano: Inteiro (INT) — Ex: 2022
• placa: Texto até 10 caracteres (VARCHAR(10)) — Ex: ABC-1234 ou ABC1D23

2. Arquivos Obrigatórios do Projeto

Seguindo a arquitetura vista em aula, o projeto deve ser dividido nos seguintes arquivos:

1. conexao.php: Responsável pela conexão com o banco de dados GaragemDB.

2. insert.php (Cadastrar): Formulário HTML para inserir um novo veículo (modelo, 
marca, ano e placa) e código PHP para gravar os dados no banco.

3. select.php (Listar/Relatório): Página que consulta o banco e exibe todos os veículos 
cadastrados em uma tabela HTML organizada.

4. update.php (Atualizar): Página que lista os veículos com um botão "Editar". Ao clicar, 
os dados do veículo devem preencher o formulário (via JavaScript) para que possam ser 
alterados e salvos no banco.

5. delete.php (Excluir): Página que lista os veículos com um botão "Deletar". Ao clicar, 
deve exibir uma janela de confirmação em JavaScript (confirm) antes de excluir o 
registro do banco.
