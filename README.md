# 📊 Projeto Alura Store — Análise de Desempenho das Lojas

Este projeto tem como objetivo auxiliar o Sr. João, proprietário da rede **Alura Store**, a decidir **qual das suas quatro lojas** deve ser vendida com base em desempenho. Para isso, realizamos uma análise completa das vendas utilizando Python e bibliotecas de ciência de dados.

---

## 🎯 Propósito da Análise

A análise busca responder à pergunta:  
**"Qual loja da Alura Store tem o menor desempenho e deve ser vendida?"**

Foram avaliadas as seguintes métricas:

- Faturamento total por loja  
- Categorias de produtos mais populares  
- Média de avaliação dos clientes  
- Produtos mais e menos vendidos  
- Custo médio de frete  
- Distribuição geográfica das vendas (latitude e longitude)

---

📊 Exemplos de Gráficos e Insights
- Gráfico de barras com o faturamento total por loja.
- Gráfico de pizza com a distribuição das categorias mais vendidas.
- Boxplot com o custo médio de frete por loja.
- Gráfico de dispersão geográfica das vendas por latitude e longitude.
- Mapa de calor (Heatmap) da densidade de vendas por região.
- Mapa interativo (Folium) com marcadores coloridos por loja.

---

🔍 Alguns insights:
- A loja com menor faturamento também apresentou a menor média de avaliação dos clientes.
- Certas lojas concentram suas vendas em regiões específicas, o que pode indicar saturação ou limitação logística.
- Produtos de determinadas categorias são consistentemente mais populares entre os clientes.

---

🧪 Como Executar o Notebook
1. Instale as dependências necessárias:

- pip install pandas matplotlib seaborn folium

2. Abra o notebook AluraStoreBr.ipynb no Google Colab ou VSCode com Jupyter:

- No Google Colab: basta enviar o notebook e executá-lo célula por célula.
- No VSCode: abra com a extensão Jupyter e execute as células sequencialmente.

3. Certifique-se de estar conectado à internet para que os dados sejam carregados das URLs corretamente.

4. Para ver o mapa interativo fora do notebook, rode:

- m.save('mapa_interativo_lojas.html')

E abra o arquivo no navegador.

---

👨‍💻 Este projeto foi desenvolvido como parte de um desafio de Data Science da Alura com aplicação de técnicas reais de análise de dados e visualização interativa.

