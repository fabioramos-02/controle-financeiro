# Especificação do Trabalho - App Controle de Pedidos

**Aluno:** Fabio Willian Lima Ramos

## Visão Geral do Software
O aplicativo é uma plataforma de pedidos de comida que permite aos usuários se cadastrarem, fazerem login, visualizarem itens disponíveis para pedido, adicionarem itens ao pedido, confirmarem pedidos e visualizarem pedidos feitos anteriormente. O aplicativo também envia notificações com som personalizado ao confirmar um pedido.

## Papéis e Usuários
### Usuários
- **Cliente**: Usuário que utiliza o aplicativo para fazer pedidos de comida.

### O que cada usuário pode fazer
- **Cliente**:
  - Cadastrar-se no aplicativo.
  - Fazer login no aplicativo.
  - Visualizar itens disponíveis para pedido.
  - Adicionar itens ao pedido.
  - Confirmar pedidos.
  - Visualizar pedidos feitos anteriormente.
  - Receber notificações ao confirmar um pedido.

## Requisitos Funcionais
### Cadastro de Usuário
- O sistema deve permitir que o usuário se cadastre com nome, telefone, email e senha.
- O sistema deve garantir que o nome não contenha números.
- O sistema deve criptografar a senha antes de armazená-la no banco de dados.

### Login de Usuário
- O sistema deve permitir que o usuário faça login com email e senha.
- O sistema deve verificar a senha criptografada ao fazer login.

### Menu Principal
- O sistema deve exibir um menu principal com opções para fazer um pedido e ver pedidos feitos.

### Fazer Pedido
- O sistema deve exibir uma lista de itens disponíveis para pedido.
- O sistema deve permitir que o usuário adicione itens ao pedido.
- O sistema deve exibir o total do pedido.
- O sistema deve permitir que o usuário confirme o pedido.
- O sistema deve enviar uma notificação com som personalizado ao confirmar o pedido.

### Ver Pedidos Feitos
- O sistema deve exibir uma lista de pedidos feitos pelo usuário.
- O sistema deve exibir uma mensagem caso não haja pedidos feitos.
- O sistema deve permitir que o usuário volte ao menu principal.

## Requisitos Não Funcionais
### Segurança
- O sistema deve criptografar a senha do usuário usando a biblioteca `bcrypt`.
- O sistema deve garantir que a senha criptografada seja verificada ao fazer login.

### Notificações
- O sistema deve criar um canal de notificação para pedidos.
- O sistema deve enviar notificações com som personalizado ao confirmar um pedido.

### Interface do Usuário
- O sistema deve usar cores e strings definidas nos arquivos `colors.xml` e `strings.xml`.
- O sistema deve exibir mensagens de erro e sucesso apropriadas.

### Desempenho
- O sistema deve carregar itens e pedidos de forma assíncrona para evitar travamentos na interface do usuário.

## Entradas Necessárias
- Nome, telefone, email e senha para cadastro de usuário.
- Email e senha para login de usuário.
- Seleção de itens para fazer um pedido.

## Processamento Realizado pelo App
- Criptografia da senha do usuário ao cadastrar.
- Verificação da senha criptografada ao fazer login.
- Carregamento de itens disponíveis para pedido.
- Adição de itens ao pedido.
- Cálculo do total do pedido.
- Armazenamento de pedidos no banco de dados.
- Envio de notificações ao confirmar um pedido.

## Relatórios e Saídas do App
- Lista de itens disponíveis para pedido.
- Total do pedido.
- Notificações de confirmação de pedido.
- Lista de pedidos feitos pelo usuário.
- Mensagens de erro e sucesso apropriadas.
