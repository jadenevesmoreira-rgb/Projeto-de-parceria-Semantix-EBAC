# Identificação de Perfis Sociodemográficos entre Candidatos a Vereador nas Eleições Municipais Brasileiras de 2024 por meio de Técnicas de Clusterização

## Sobre o projeto

Este projeto aplica técnicas de **Machine Learning Não Supervisionado** para identificar perfis sociodemográficos entre os candidatos ao cargo de vereador nas eleições municipais brasileiras de 2024.

A pesquisa busca compreender se existem grupos distintos de candidatos que compartilham características semelhantes relacionadas a gênero, idade, cor/raça, escolaridade e estado civil, contribuindo para o debate sobre representação política, recrutamento partidário e diversidade nas disputas eleitorais.

Além do objetivo substantivo na área de Ciência Política, o projeto demonstra a aplicação prática de técnicas de Ciência de Dados na exploração de grandes bases públicas.

---

## Objetivos

* Identificar perfis sociodemográficos entre candidatos a vereador.
* Explorar padrões ocultos presentes na base de dados.
* Aplicar técnicas de clusterização para segmentação dos candidatos.
* Demonstrar o uso de métodos de Machine Learning em pesquisas sociais.

---

## Base de dados

Os dados utilizados são provenientes do **Tribunal Superior Eleitoral (TSE)**, por meio do portal de Dados Abertos, contendo informações sobre os candidatos registrados para as Eleições Municipais de 2024.

### Variáveis utilizadas

* Gênero
* Idade
* Cor/Raça
* Escolaridade
* Estado Civil

---

## Metodologia

O projeto foi desenvolvido seguindo as principais etapas de um fluxo de Ciência de Dados:

1. Importação e limpeza dos dados
2. Análise exploratória
3. Tratamento de inconsistências e remoção de outliers
4. Preparação das variáveis
5. Codificação das variáveis categóricas (One-Hot Encoding)
6. Padronização dos dados
7. Definição do número ideal de clusters
8. Aplicação do algoritmo K-Means
9. Avaliação dos agrupamentos
10. Interpretação dos perfis encontrados

---

## Técnicas utilizadas

* K-Means Clustering
* One-Hot Encoding
* Padronização com StandardScaler
* Método do Cotovelo (Elbow Method)
* Silhouette Score
* Estatística Descritiva
* Visualização de Dados

---

## Tecnologias

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Plotly
* Google Colab

---

## Estrutura do projeto

```text
├── Projeto_de_parceria_Semantix.ipynb
├── dados/
├── imagens/
├── README.md
```

---

## Principais resultados

A aplicação do algoritmo K-Means permitiu identificar grupos de candidatos com perfis sociodemográficos distintos, evidenciando padrões relacionados à idade, gênero, escolaridade, cor/raça e estado civil.

Os resultados demonstram o potencial da clusterização para apoiar análises sobre representação política e diversidade eleitoral, permitindo que os próprios dados revelem estruturas e segmentos existentes sem categorias previamente definidas.

---

## Possíveis aplicações

* Ciência Política Computacional
* Estudos Eleitorais
* Representação Política
* Políticas Públicas
* Ciência de Dados aplicada às Ciências Sociais

---

## Autor

**Jade Neves**

Mestre em Ciência Política | Cientista de Dados

Interesses de pesquisa:

* Ciência de Dados
* Machine Learning
* Ciência Política Computacional
* Políticas Públicas
* Análise de Dados
