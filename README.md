# Especificação do Trabalho - App de Controle Financeiro

**Aluno:** Fabio Willian Lima Ramos

## Visão Geral do Software:
Este projeto visa criar um aplicativo de controle financeiro, desenvolvido em Android Studio utilizando Java. O objetivo é permitir que o usuário gerencie seus gastos de maneira eficiente, registrando entradas e saídas de dinheiro, categorizando seus gastos e gerando relatórios para facilitar o acompanhamento de seu orçamento.

## Funcionalidades Principais:

- **Criação de Categorias:**  
  O usuário pode criar categorias personalizadas para organizar suas despesas (por exemplo, Alimentação, Transporte, Lazer, etc.).

- **Registros de Entradas e Saídas:**  
  O aplicativo permitirá o usuário registrar suas entradas (receitas) e saídas (despesas), com a possibilidade de detalhar o valor e a categoria.

- **Relatório de Gastos:**  
  O usuário poderá gerar relatórios financeiros com base nos dados registrados, visualizando os gastos por categoria e período (mensal, semanal, etc.).

## Papéis dos Usuários:

- **Usuário Comum:**  
  O usuário pode criar uma conta, cadastrar suas entradas e saídas, definir categorias para suas despesas, e gerar relatórios de seus gastos.

## Requisitos Funcionais:

1. O app deve permitir o **cadastro de usuário**.
2. O app deve permitir ao usuário **adicionar e visualizar entradas e saídas** de dinheiro.
3. O app deve possibilitar a **criação de categorias personalizadas** para cada tipo de gasto.
4. O app deve **gerar relatórios** sobre os gastos, com opções de filtragem por categoria e período.

## Armazenamento:
Utilização de **banco de dados** para armazenar os dados dos usuários, registros de entradas e saídas, e categorias criadas.

## Requisitos Obrigatórios:

- **Tela Inicial de Login e Cadastro de Usuário:**  
  O app terá uma tela de login, com a opção de cadastro, onde o usuário pode criar uma conta com foto e senha (armazenada como hash).

- **Tratamento de Erros:**  
  O app irá tratar erros como campos vazios, entradas inválidas (por exemplo, texto em campos numéricos) e outros erros comuns.

## Requisitos Recomendados:

- **Usabilidade:**  
  O app será desenvolvido com uma interface **intuitiva**, de fácil navegação e esteticamente agradável.

- **Acessibilidade:**  
  Consideração de recursos que atendem às necessidades de **usuários com deficiências**.

- **Segurança:**  
  **Criptografia da senha** e controle de acesso seguro aos dados do usuário.
