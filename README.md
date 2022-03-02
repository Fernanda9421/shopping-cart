# Projeto Shopping Cart

Esse projeto foi desenvolvido durante o curso de Desenvolvimento Web, na Trybe.



## Sumário

- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Contexto](#contexto)
- [Data de desenvolvimento do projeto](#data-de-desenvolvimento-do-projeto)
- [Instruções para clonar o projeto](#instruções-para-clonar-o-projeto)
- [Resultado](#resultado)
- [Funcionalidades](#funcionalidades)



## Tecnologias utilizadas

- JavaScript (Requisições a uma API do Mercado Livre, Funções assíncronas);
- CSS 3;
- HTML 5;
- Testes unitários.



## Contexto

Nesse projeto foi desenvolvido um **carrinho de compras** dinâmico! Os dados necessários foram consumidos diretamente de uma API do Mercado Livre.



## Data de desenvolvimento do projeto

  - Novembro / 2021.



## Instruções para clonar o projeto

1. Clone o repositório

  * `git clone git@github.com:Fernanda9421/shopping-cart.git`
  * Entre na pasta do repositório:
    * `cd shopping-cart`

2. Instale as dependências
   - `npm install`



## Resultado:

Após clonar o projeto, o resultado no Browser será semelhante à este gif

![Project Gif](./prototipo.gif)



## Funcionalidades:

#### Listagem de Produtos

Os produtos dispostos na tela são consumidos da API do Mercado Livre, com o seguinte *endpoint*:

```javascript
"https://api.mercadolibre.com/sites/MLB/search?q=computador"
```

#### Adicionar produtos ao carinho de compras

É possível adicionar produtos no carrinho de compras ao clicar no botão `Adicionar ao carrinho!`. Os itens adicionados ficam salvos no LocalStorage.

Ao adicionar um item, suas informações aparecem no Carrinho de Compras, visível no lado direito da página.

#### Remover produtos do carrinho de compras

Ao clicar no produto que está no Carrinho de Compras, o mesmo é removido da lista.

#### Valor total dos produtos

É possível visualizar a soma de preço dos produtos adicionados. Esse valor aparece no campo `Preço total`, e é atualizado a medida que se adiciona ou remove itens do Carrinho

#### Limpar o Carrinho de Compras

Há um botão `Esvaziar carrinho`, que ao ser clicado, remove todos os itens do Carrinho de Compras.