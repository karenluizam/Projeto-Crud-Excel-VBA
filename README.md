# Projeto-Crud-Excel-VBA

## 🖥 Sobre o projeto
O projeto consiste em formulários de CRUD funcionais feitos em VBA para um pequeno negócio de cosméticos naturais.
O projeto em grupo fez parte da disciplina de Programação de Microinformática do 1° semestre do curso de Análise e Desenvolvimento de Sistemas da FATEC Ipiranga.
Fui a líder do projeto, fazendo divisão de tarefas e dando feedbacks aos integrantes da equipe.

❗ Antes de abrir o arquivo, abra suas propriedades e habilite "Desbloquear" em Segurança.

## 👩‍💻 Tecnologias usadas
O Projeto foi feito usando Visual Basic for Applications do Excel.
As imagens foram editadas no Canva.

## 📝O Projeto
No projeto, escolhemos formulários que poderiam ser úteis para o microempreendedor usar em seu trabalho. São eles:
- CRUD de Clientes
- CRUD de Produtos
- CRUD de Pedidos
- CRUD de Estoque Bruto
- Controle de Validades

O arquivo também apresenta uma guia de instruções para o usuário e tela de login.


### ✍ Cadastro
![CadastroCliente](https://github.com/karenluizam/Projeto-Crud-Excel-VBA/blob/main/ImagensCRUD/adicionar%20cliente.png?raw=true)

O cadastro de todos os formulários têm os botões de Adicionas, Limpar Campos e Fechar. O programa gera os IDs automaticamente, sem repetição mesmo se excluído, utilizando uma planilha apenas para registros de ID.

### 🚫 Exclusão
![ExclusãoPedido](https://github.com/karenluizam/Projeto-Crud-Excel-VBA/blob/main/ImagensCRUD/excluir%20pedido.png?raw=true)


A exclusão pode ser feita pelo formulário de gerenciamento. O cadastro dele ser selecionado para ser excluído, e uma mensagem de confirmação aparecerá para confirmação. O ID do cadastro também é excluído e não será reutilizado.

### 🔍 Pesquisa
![PesquisaProduto](https://github.com/karenluizam/Projeto-Crud-Excel-VBA/blob/main/ImagensCRUD/pesquisas%20produtos.png?raw=true)

A pesquisa pode ser feita nos formulários de gerenciamento. Embaixo da barra de pesquisa, há os termos que podem ser pesquisados naquele formulário, ao lado, um botão para limpar a barra de pesquisa.

### 🔃 Edição
![EdicaoPedido](https://github.com/karenluizam/Projeto-Crud-Excel-VBA/blob/main/ImagensCRUD/editarpedido.png?raw=true)

Um cadastro pode ser editado clicando no botão Editar no formulário de gerenciamento. O formulário de edição é basicamente igual ao de cadastro, porém já apresenta os dados a serem editados. Além do botão de salvar, o formumário também apresenta o botão de Limpar Campos e Fechar.

### 📅 Controle de Validades
![ControleValidade](https://github.com/karenluizam/Projeto-Crud-Excel-VBA/blob/main/ImagensCRUD/controle.png?raw=true)

Como diferencial, foi incluído o formulário de controle de validades dos produtos, onde podem ser visualizados os produtos por ordem de ID ou por ordem de dias restantes para data de validade, clicando no botão de ordenar por Dias Restantes. O Formulário também apresenta um aviso ao lado dos produtos que tenham 40 dias de validade ou menos.

