# Sistema_de_Recomendacao com EfficientNetB0

Este projeto é um protótipo de sistema de recomendação baseado em imagens.
Ele utiliza visão computacional para identificar e sugerir produtos semelhantes a partir de uma escolha inicial feita pelo usuário.

# Como funciona

O sistema baixa automaticamente imagens de diferentes categorias de produtos usando icrawler.

O usuário visualiza miniaturas e escolhe um produto de interesse.

O modelo pré-treinado EfficientNetB0 (ImageNet) analisa a imagem selecionada.

O sistema mostra o produto escolhido junto com imagens visualmente semelhantes, simulando um sistema de recomendação de produtos.

# Requisitos

Instale as dependências necessárias antes de rodar o código:

pip install icrawler tensorflow tensorflow_hub matplotlib pillow --upgrade -q

# Como usar

Defina as classes de produtos na variável classes (ex.: ["sneakers", "handbag", "watch"]).

Execute o script para baixar automaticamente algumas imagens de cada classe.

O sistema exibirá as miniaturas e pedirá que o usuário selecione um produto digitando o número correspondente.

O modelo mostrará o produto escolhido e imagens similares com suas respectivas predições.

# Tecnologias

Python

TensorFlow / Keras

EfficientNetB0 (pré-treinado no ImageNet)

icrawler

