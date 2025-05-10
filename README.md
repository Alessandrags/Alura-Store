# Análise de Desempenho das Lojas Alura Store

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oUBYATjNsV7vghjaj5lYsZxS235fKmg6)


Este projeto foi desenvolvido como parte do curso de Data Science da Alura (e do projeto #ONE) e tem como objetivo auxiliar o Senhor João a tomar uma decisão estratégica sobre qual loja da sua rede Alura Store vender para iniciar um novo empreendimento. Através da análise de dados de vendas, desempenho e avaliações de quatro lojas fictícias, buscamos identificar a loja com menor eficiência para apresentar uma recomendação embasada em dados.

## 🎯 Objetivo

Identificar a loja da rede Alura Store com o menor desempenho, considerando faturamento, número de vendas, avaliação dos clientes e outros indicadores relevantes, para auxiliar na decisão de qual unidade vender.

## 🛠️ Ferramentas e Tecnologias Utilizadas

* **Python:** Linguagem de programação utilizada para análise de dados.
* **Pandas:** Biblioteca Python para manipulação e análise de dados tabulares (DataFrames).
* **Matplotlib:** Biblioteca Python para criação de gráficos e visualizações de dados.
* **Folium:** Biblioteca Python para criação de mapas interativos.
* **Google Colaboratory:** Ambiente online para execução do código Python e análise de dados.
* **GitHub:** Plataforma de hospedagem de código para versionamento e colaboração.

## 💾 Dados

Os dados utilizados nesta análise são provenientes de quatro arquivos CSV distintos, cada um representando uma das lojas da Alura Store:

* `loja_1.csv`
* `loja_2.csv`
* `loja_3.csv`
* `loja_4.csv`

Os arquivos contêm informações sobre vendas, incluindo preço dos produtos, categoria, avaliação da compra, frete, latitude e longitude (para visualização geográfica).

## 📊 Análise Realizada

A análise exploratória dos dados envolveu as seguintes etapas:

* **Carregamento e Manipulação de Dados:** Utilização da biblioteca Pandas para ler e estruturar os dados de cada loja em DataFrames.
* **Cálculo do Faturamento:** Determinação do faturamento total de cada loja e o faturamento total da rede.
* **Análise de Vendas:** Cálculo do número de vendas e do faturamento médio por venda em cada loja.
* **Ranking de Faturamento:** Criação de um ranking das lojas com base no faturamento, incluindo a participação percentual de cada loja e a diferença em relação à líder.
* **Análise por Categoria de Produto:**
    * Quantidade de produtos vendidos por categoria em cada loja e o total geral.
    * Valor total faturado por categoria em cada loja e o total geral.
    * Participação percentual do valor faturado por categoria em cada loja.
* **Avaliação das Lojas:**
    * Cálculo da média de avaliação das compras por loja.
    * Análise da média percentual das avaliações por categoria e por loja de forma consolidada.
* **Análise de Produtos Destaque:** Identificação dos produtos mais e menos vendidos em cada loja, tanto em quantidade quanto em valor, incluindo a participação percentual no faturamento da loja.
* **Custo de Frete:** Cálculo do frete médio por loja.
* **Visualização de Dados:** Criação de gráficos utilizando a biblioteca Matplotlib para melhor compreensão dos resultados:
    * Gráfico de barras do faturamento por loja.
    * Gráfico de pizza da participação no faturamento total.
    * Gráfico de barras da média de avaliações por loja.
    * Gráfico de linhas do frete médio por loja.
    * Mapa de calor (Heatmap) utilizando a biblioteca Folium para visualizar a distribuição geográfica das vendas.

## 💡 Conclusão e Recomendação

A análise do desempenho das quatro lojas Alura Store revela que a **Loja 4** apresenta o menor faturamento (R$ 1.384.497,58) e uma avaliação de clientes ligeiramente inferior à das Lojas 2 e 3. Apesar do menor frete médio, seu desempenho financeiro geral é o mais fraco, com uma diferença significativa de R$ 150.011,54 para a líder (Loja 1).

**Recomendamos a venda da Loja 4.**

Esta decisão é baseada em seu desempenho financeiro inferior e menor potencial de crescimento em comparação com as demais lojas. A venda permitirá que o Senhor João foque em suas unidades mais rentáveis (Lojas 1, 2 e 3) e invista em melhorias estratégicas para otimizar ainda mais seus resultados.

Após a venda, sugere-se uma análise detalhada das lojas remanescentes para identificar oportunidades de otimização e crescimento.

## 🚀 Próximos Passos

* Análise mais aprofundada de outros fatores que podem influenciar a decisão, como custos operacionais de cada loja, lucratividade por produto, sazonalidade das vendas, etc.
* Realização de uma análise de sensibilidade para avaliar o impacto da venda de diferentes lojas.
* Integração de dados de outras fontes, como dados de marketing e estoque.

## 🧑‍💻 Como Executar o Código

1.  Clone este repositório para sua máquina local:
    ```bash
    git clone [https://github.com/Alessandrags/Alura-Store.git](https://github.com/Alessandrags/Alura-Store.git)
    ```
2.  Abra o arquivo `AluraStoreBr.ipynb` no Google Colaboratory ou em um ambiente Jupyter Notebook com as bibliotecas Pandas, Matplotlib e Folium instaladas.
3.  Execute as células do notebook para reproduzir a análise e visualizar os resultados.

## 🤝 Contribuição

Este é um projeto individual realizado como parte de um desafio de Data Science. No entanto, sinta-se à vontade para abrir issues e propor melhorias!

## 📄 Licença

MIT License

Este projeto foi desenvolvido como parte do Challenge de Data Science da Alura.

A licença MIT completa pode ser encontrada em [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT).

**Feito com ❤️ por Alessandrags**
