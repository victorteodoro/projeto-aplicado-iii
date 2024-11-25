# Projeto Aplicado 3 - Recomendação de livros

Aqui encontram-se datasets, análises e resultados da disciplina Projeto Integrado III do curso de Ciência de Dados do Mackenzie

## Membros

| Nome                         | RA       | Email                       |
| ---------------------------- | -------- | --------------------------- |
| André Dalle Vedove Canassa   | 10415817 | 10415817@mackenzista.com.br |
| Valdo Alvim da Rocha Junior  | 10414936 | 10414936@mackenzista.com.br |
| Victor José de Souza Teodoro | 10414609 | 10414609@mackenzista.com.br |

## Introdução

O projeto realizado pela equipe da Universidade Presbiteriana Mackenzie, Faculdade de Computação e Informática, tem como objetivo desenvolver um modelo de recomendação de livros baseado em avaliações de usuários, utilizando técnicas de aprendizado de máquina para analisar padrões de preferências e comportamentos de leitura. A meta principal é criar um sistema capaz de sugerir livros personalizados para cada usuário, com base em suas avaliações anteriores e nas similaridades entre usuários e livros, promovendo uma experiência de recomendação precisa e eficiente.

Os dados utilizados foram coletados do site Kaggle e compreendem informações de avaliações de livros, usuários e informações sobre os livros.

O projeto define um modelo analítico que inclui o uso da linguagem de programação Python e bibliotecas, sendo elas: pandas, numpy, matplotlib, seaborn, sklearn e scipy.sparse. O cronograma detalhado inclui encontros síncronos, períodos de trabalho e entregas das etapas do projeto.

## Origem dos Dados

Os dados utilizados neste projeto foram obtidos a partir do conjunto de dados disponível na plataforma Kaggle, especificamente do conjunto intitulado "Book Recommender System" [Fonte dos dados aqui](https://www.kaggle.com/datasets/rxsraghavagrawal/book-recommender-system/code).

### Descrição dos Dados

1. **BX-Books.csv**: contém informações sobre os livros, e cada coluna descreve uma característica de cada livro listado.

   Colunas relevantes:

   - `ISBN`: Identificador único para cada livro
   - `Book-Title`: O título do livro
   - `Book-Author`: O autor do livro
   - `Year-Of-Publication`: O ano de publicação do livro
   - `Publisher`: A editora que publicou o livro
   - `Image-URL-S, Image-URL-M, Image-URL-L`: URLs de imagens da capa do livro em três diferentes tamanhos (pequeno, médio e grande)

2. **BX-Users.csv**: Este arquivo contém revisões dos imóveis listados.

   Colunas:

   - `User-ID`: Identificador único para cada usuário
   - `Location`: A localização do usuário, geralmente no formato "cidade, estado, país"
   - `Age`: A idade do usuário

3. **BX-Book-Ratings.csv**: Este arquivo contém revisões dos imóveis listados.

   Colunas:

   - `User-ID`: Identificador único para cada usuário
   - `ISBN`: Identificador único para cada livro
   - `Book-Rating`: A avaliação dada ao livro pelo usuário.
