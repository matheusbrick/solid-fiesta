# solid-fiesta
Sistema de recomendação de produtos.

# Business Understanding

Durante a pandemia os números de vendas da Razzle Dazzle (e-commerce de variedades) dispararam, bem como o da concorrência. Uma das maneiras de se destacar nesse mercado cada vez mais competitivo é oferecer o produto certo para a pessoa certa.
Então, você foi contratado desenvolver pelo menos um modelo de recomendação, que será disponibilizado no novo site da empresa. Além do modelo, é necessário informar qual o melhor momento para usá-lo, em propagandas, quando o cliente estiver fazendo uma pesquisa ou quando o cliente estiver vendo um produto. É fundamental que isso seja pensado no desenvolvimento do modelo.

# Data Preparation

Merge de dataframes para consolidar as informações. (merge, agg)

# Sampling

Utilização dos 1500 produtos mais avaliados e mais populares (maior numero de pedidos de compra).
Otimização de processamento e garantir recomendação de melhores produtos

# Matrix similarity

Usando a tecnica de similiradade de cosenos para relacionar produtos e usuários.

# Recomendação

Através do input do produto visitado:

1- Recomendação dos 10 produtos com maior numero de avaliações e com maior similaridade.
2- Recomendação dos 10 produtos com maior numero de compras na mesma categoria do produto visitado e com maior similaridade.

No caso de o produto não se encaixar entre os top 1500 produtos da amostragem, a recomendação é dos 10 primeiros listados (global)

1- Recomendação dos 10 produtos com maior numero de avaliações.
2- Recomendação dos 10 produtos com maior numero de compras na mesma categoria do produto visitado.
