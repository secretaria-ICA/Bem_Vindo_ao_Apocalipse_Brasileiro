<!-- antes de enviar a versão final, solicitamos que todos os comentários, colocados para orientação ao aluno, sejam removidos do arquivo -->
# Bem vindo ao Apocalipse Brasileiro

#### Aluno: [Rodrigo Link Federizzi](https://github.com/rodrigolink)
#### Orientadores: [Manoela Kohler](https://github.com/manoelakohler) e [Felipe Borges](https://github.com/link_do_github).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

---

### Resumo

<!-- trocar o texto abaixo pelo resumo do trabalho, em português -->

O objetivo do trabalho é criar um índice para cada município do Brasil que indique a sua adequação em um cenário pós-apocalíptico, visando a sobrevivência de uma ou mais pessoas. Reunimos diversos bancos de dados com informações municipais de modo a construir indicadores que representem o quão isolada é a cidade, a densidade populacional, a disponibilidade de energia e área para produção de alimentos, a estabilidade do clima, entre outros. A partir desses indicadores, criamos o ISH - Índice de Sobrevivência Humana, e podemos ranquear todas as cidades do país, encontrando aquelas que são as mais adequadas para garantir a continuidade da Humanidade.

Uma vez que tenhamos o ISH para todos os municípios, podemos simular a fuga a partir de uma dada cidade. Tendo a lista de vizinhos, sorteamos um deles e fazemos uma avaliação se devemos mudar de cidade ou não. Para isso, usamos um método de otimização conhecido como simulated annealing, que possibilita explorar uma área maior do domínio ao ter uma probabilidade, mesmo que pequena, de que o sistema vá para regiões piores. Simulamos um grande conjunto de fugas e terminamos com três produtos: a rota que termina na cidade com maior ISH, a evolução do ISH durante esta rota e um heatmap, mostrando todas as cidades que foram visitadas em pelo menos uma das fugas.

### Abstract <!-- Opcional! Caso não aplicável, remover esta seção -->

<!-- trocar o texto abaixo pelo resumo do trabalho, em inglês -->

The objective of this work is to create an index for each municipality in Brazil that indicates its suitability in a post-apocalyptic scenario, aiming at the survival of one or more people. We bring together several databases with municipal information in order to build indicators that represent how isolated the city is, the population density, the availability of energy and area for food production, climate stability, among others. Based on these indicators, we created the HSI - Human Survival Index, and we can rank all the cities in the country, finding those that are the most adequate to guarantee the continuity of humanity.

Once we have the HSI for all municipalities, we can simulate the escape from a given city. Having the list of neighbors, we draw one of them and make an assessment if we should move to this other city or not. For this, we use an optimization method known as simulated annealing, which makes it possible to explore a larger area of ​​the domain by having a probability, even if small, that the system will go to worse regions. We simulate a large set of escapes and end up with three products: the route that ends in the city with the highest HSI, the evolution of the HSI during this route, and a heatmap showing all the cities that were visited in at least one of the escapes.

---

Matrícula: 192.671.125

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
