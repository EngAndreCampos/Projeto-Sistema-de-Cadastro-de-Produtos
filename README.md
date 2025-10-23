# Sistema de Cadastro de Produtos

Este é um programa simples que permite registrar produtos de uma loja de roupas de forma organizada.  
O sistema lê os dados de cada produto (nome, preço e categoria) fornecidos pelo usuário, cria um objeto da classe `Produto` e exibe as informações em um formato padronizado.

## Funcionalidades

- Recebe os dados do produto em uma única linha: **nome**, **preço** e **categoria**.
- Cria um objeto da classe `Produto` com os dados informados.
- Exibe os dados do produto no formato:  
Produto: [nome] | Categoria: [categoria] | Preco: R$ [preco]

Explicação do código:

Construtor inicializa nome, preco e categoria.

O método exibirProduto() usa System.out.printf para formatar o preço com duas casas decimais.

No Main, os dados são lidos em uma única linha e separados corretamente.

O objeto Produto é criado e seu método de exibição é chamado para mostrar a saída no formato exigido.

Exemplo de execução:

Entrada: Jaqueta 199.90 Inverno
Saída: Produto: Jaqueta | Categoria: Inverno | Preco: R$ 199.90
