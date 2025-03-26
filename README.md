🔬 Pre-processamento e Classificação com KNN, Árvore de Decisão e Random Forest

Este projeto tem como objetivo aplicar técnicas de pré-processamento de dados e avaliar a performance de três algoritmos de classificação: K-Nearest Neighbors (KNN), Árvore de Decisão e Random Forest.

📊 Objetivo

Realizar o pré-processamento de um conjunto de dados, incluindo remoção de atributos, tratamento de valores ausentes e transformação de variáveis.

Avaliar e comparar os resultados de diferentes algoritmos de classificação.

📂 Conjunto de Dados

O dataset utilizado: (disponível em https://drive.google.com/file/d/1TvU-tuY-XJf4wzEQKyqVDPuFcDlyOeTk/view?usp=sharing) contém informações que passaram pelas seguintes etapas de tratamento:

Remoção dos atributos: node, res e dg.

Exclusão de todas as instâncias com valores ausentes.

Transformação do atributo "Activity":

Valores ≤ 50: "neg"

Valores > 50: "pos"

Divisão do dataset em treino e teste (75%/25%), com semente aleatória fixada em 43.

⚙️ Tecnologias Utilizadas

Python

Pandas

Scikit-learn

🔄 Fluxo do Projeto

Carregamento e Limpeza dos Dados:

Remoção de atributos irrelevantes e valores ausentes.

Transformar variáveis numéricas em categóricas.

Divisão em Treino e Teste:

75% para treino e 25% para teste (random_state=43).

Modelagem e Avaliação:

KNN: Testando os valores de K no intervalo [9, 10, 11].

Árvore de Decisão: Identificação do atributo mais importante.

Random Forest: 100 árvores com profundidade máxima de 3.

🔍 Principais Resultados

Melhor valor de K no KNN: K = 10.

Atributo mais importante na Árvore de Decisão: Burts.contraint.

Algoritmo com melhor performance: Random Forest.

💻 Como Executar o Projeto

Clone o repositório:

   git clone https://github.com/seu-usuario/preprocessamento-e-classificacao-ML.git

Instale as dependências (recomendo o uso de um ambiente virtual):

   pip install -r requirements.txt

Execute o notebook em um ambiente Jupyter ou Google Colab.

📊 Contribuição

Fique à vontade para abrir issues ou enviar um pull request com melhorias e novas abordagens.

