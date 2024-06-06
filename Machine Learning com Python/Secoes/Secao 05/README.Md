# Machine Learning com Python

Este repositório é um registro de todo o meu trabalho e avanço no curso "Machine Learning com Python". Este curso é abrangente e cobre desde os conceitos fundamentais de machine learning e da linguagem Python, até técnicas mais avançadas e específicas do campo de aprendizado de máquina.

## Seção 5: Aprendizado Supervisionado: Regressão

A Seção 5 é dedicada ao estudo do aprendizado supervisionado para problemas de regressão. Abaixo está um resumo dos tópicos abordados nesta seção:

### Regressão Linear Simples

- Modelo matemático linear capaz de realizar previsões.
- Equação: \( y = mx + b \)
- Métricas de avaliação: \( R² \), erro absoluto, erro médio absoluto, erro quadrático médio, raiz do erro quadrático médio.

### Regressão Linear Múltipla

- Quando possui mais de uma variável independente.
- Utiliza o método dos mínimos quadrados.
- Importante verificar pressupostos como linearidade, homocedasticidade, e ausência de multicolinearidade.

### Regressão Polinomial

- Ajuste de uma equação não linear por meio de funções polinomiais.
- Pode modelar relações mais complexas que a regressão linear simples.

### Regressão por Vetores de Suporte (SVR)

- Utiliza o conceito de margem para regressão.
- Parâmetro importante: kernel.
- Requer padronização de escala.

### Regressão com Árvore de Decisão

- Modelo baseado em estrutura de árvore.
- Parâmetros principais: profundidade e `random_state`.
- Pode capturar relações não lineares sem necessidade de transformação dos dados.

### Regressão com Random Forest

- Cria várias árvores de decisão aleatórias.
- Utiliza o método Ensemble para melhores resultados.
- Parâmetros principais: `n_estimators`, `criterion`, `max_depth`, `random_state`.

### Regressão com XGBoost

- Evolução do Gradient Boosting baseada em árvores de decisão.
- Potente e amplamente utilizado em competições de machine learning.
- Parâmetros principais: `n_estimators`, `max_depth`, `learning_rate`, `objective`.

### Regressão com LightGBM

- Versão otimizada e de alta velocidade do Gradient Boosting.
- Alta performance em grandes conjuntos de dados.
- Parâmetros principais: `num_leaves`, `max_depth`, `learning_rate`, `n_estimators`.

### Regressão com CatBoost

- Evolução do Gradient Boosting otimizada para eficiência.
- Lida automaticamente com variáveis categóricas.
- Parâmetros principais: `iterations`, `learning_rate`, `depth`, `random_state`.

## Análise e Tratamento de Dados

### Passos

1. Verificar valores faltantes: `isnull().sum()`
2. Analisar os tipos de atributos: `dtypes`
3. Análise estatística: `describe()`
4. Análise de outliers utilizando boxplots.

## Correlação

### Coeficiente de Correlação Linear (Pearson)

- Mede a força da relação linear entre duas variáveis.
- Correlação forte: \( 0.8 \le r < 1 \)
- Correlação moderada: \( 0.5 \le r < 0.8 \)
- Correlação fraca: \( 0 \le r < 0.5 \)

### Coeficiente de Determinação (R²)

- Avalia a qualidade do ajuste de um modelo de regressão.

### Coeficiente de Correlação de Spearman e Kendall

- Spearman: Utilizado para dados não lineares e ordinais.
- Kendall: Indicado para pequenos conjuntos de dados ou com valores repetidos.

### Resumo

Na pasta [Resumo](./Resumo/), você encontrará um **resumo detalhado** do que foi abordado nesta seção, incluindo explicações e exemplos de código que ilustram os conceitos estudados.

### Exercícios

Na pasta [Exercicios](./Exercicios/), estão os exercícios propostos e suas respectivas soluções, que servem para consolidar o conhecimento adquirido sobre os fundamentos da linguagem Python.

Espero que você encontre este repositório útil e informativo. Sinta-se à vontade para explorar e aprender!
