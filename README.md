# E-commerce

Este é um projeto de **e-commerce simples** para a venda de **produtos digitais** (e-books, cursos, templates, etc.). O projeto foi desenvolvido utilizando **Laravel 12** para o backend e o **Laravel Breeze** para a autenticação e o frontend básico.

## Tecnologias Utilizadas

- **Backend**: Laravel 12
- **Frontend**: Laravel Breeze (com Blade e Tailwind CSS)
- **Pagamento**: Stripe
- **Estilos**: Tailwind CSS

## Funcionalidades

### 1. Página de Listagem de Produtos
- Exibe todos os produtos disponíveis para compra com imagem, título e preço.
- A informação dos produtos é fornecida pela API do Laravel.

### 2. Detalhes do Produto
- O usuário pode visualizar mais informações sobre cada produto, como descrição detalhada e imagens.

### 3. Carrinho de Compras
- O usuário pode adicionar produtos ao carrinho.
- Possibilidade de remover itens ou alterar a quantidade.
- Exibição do total da compra.

### 4. Checkout e Pagamento com Stripe
- O usuário pode finalizar a compra.
- Integração com Stripe para processar pagamentos de forma segura.
- Após pagamento bem-sucedido, o usuário recebe uma confirmação por e-mail com o acesso ao produto.

### 5. Administração de Produtos
- Página de administração para o usuário adicionar, editar ou remover produtos.
- Sistema de autenticação utilizando **Laravel Breeze**.

## Pré-Requisitos

Antes de rodar o projeto, você precisará ter as seguintes ferramentas instaladas:

- [PHP 8.x](https://www.php.net/downloads.php)
- [Composer](https://getcomposer.org/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Stripe Account](https://stripe.com/)

## Como Rodar o Projeto

### Backend (Laravel)

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/e-commerce.git
   cd e-commerce
