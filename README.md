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

Como Executar

Compile o programa:

javac Main.java


Execute o programa:

java Main


Digite os dados do produto na mesma linha, separados por espaço:

Jaqueta 199.90 Inverno


O programa exibirá:

| **Entrada**               | **Saída**                                                  |
|----------------------------|-----------------------------------------------------------|
| Camiseta 49.90 Roupas      | Produto: Camiseta \| Categoria: Roupas \| Preco: R$ 49.90 |
| Calca 89.90 Jeans          | Produto: Calca \| Categoria: Jeans \| Preco: R$ 89.90     |
| Jaqueta 199.90 Inverno     | Produto: Jaqueta \| Categoria: Inverno \| Preco: R$ 199.90 |
| Bone 29.90 Acessorios      | Produto: Bone \| Categoria: Acessorios \| Preco: R$ 29.90  |

Certifique-se de digitar os dados na mesma linha, separados por espaço.

Este sistema pode ser expandido para suportar múltiplos produtos ou integração com um banco de dados no futuro.
