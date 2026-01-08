Este projeto realiza uma análise de séries temporais para prever o faturamento da categoria **'cool_stuff'** utilizando dados reais da plataforma Olist.

## 📊 Visualização do Modelo Final
Aqui vemos o ajuste da Regressão Polinomial (verde) sobre os dados históricos e a projeção para os próximos 30 dias (vermelho):

![Tendência e Previsão de Faturamento](imgs/Análise%20Final.png)

## 🎯 Destaques do Projeto
* **Engenharia de Dados**: Agrupamento por faturamento diário e tratamento de séries temporais.
* **Otimização de Modelo**: Comparação entre Regressão Linear e Polinomial.
* **Acurácia (R²)**: O modelo polinomial atingiu **0.47**, superando a base linear (0.42).

## 🔍 Principais Insights
1. **Curva de Maturação**: O gráfico mostra um platô inicial (2016) seguido por uma aceleração consistente em 2017.
2. **Sazonalidade**: Identificamos picos extremos de venda, como o registrado na Black Friday de Novembro de 2017.
3. **Tendência**: A categoria apresenta crescimento sólido, com projeção positiva para o próximo mês.

## 🧰 Tecnologias Utilizadas
* Python
* Pandas
* Scikit-Learn
* Matplotlib (Visualização de Dados)
