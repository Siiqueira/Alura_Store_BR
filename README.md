# 🛍️ Alura Store BR – Análise de Vendas de Lojas

📊 Projeto de análise de dados de vendas da Alura Store Br, com foco em unificação e comparação de dados, análise temporal, avaliação de custos e impacto do frete, faturamento e Análise de produto e vendas, relat. Desenvolvido em Python com Pandas e visualizações estratégicas para geração de insights comerciais e soluções.

---

## 🎯 Desafio e Objetivo
Um de nossos clientes, o Sr. João, nos procurou solicitando nossos serviços. Seu objetivo é vender uma de suas quatro lojas, com foco em reinvestir em novos projetos. Fui encarregado de identificar, por meio da análise de dados, qual das lojas apresenta o pior desempenho e, portanto, deve ser considerada para retirada do portfólio.

---

## 📊 Objetivos do Projeto

- Consolidar e padronizar dados de 4 lojas
- Tratar datas e criar colunas temporais (mês e ano)
- Calcular faturamento total, anual e mensal por loja
- Avaliar impacto do frete no custo total
- Análise exploratória, descritiva, diagnóstica, preditiva, prescritiva
- Storytelling

---

## 🛠️ Tecnologias Utilizadas

- Google Colab
- Python
- Pandas
- NumPy
- datetime
- Matplotlib.pyplot
- Matplotlib.ticker - Método ScalarFormatter e FuncFormatter(para formatar os ticks de um gráfico)
- IPython.display - Métodos display, HTML, Markdown (para melhor formatação das saídas)
- HTML
- prophet (para fazer um grafico de previsão)
- folium ( para criar um mapa de calor)
- Markdown
- IA Napkin

---

## 📁 Estrutura do Projeto

📦 Alura_Store_Br/  
│  
├── 📊 Banco de dados/  
│ └── Arquivos .csv das Lojas  
|  
│── 📈 img/  
| └── Imagens e gráficos  
|  
├── 📓 AluraStoreBr.ipynb  
├── 📜 README.md  
|── .gitignore  
|── LICENSE  
|── Relátorio.pdf  

---

## 📌 Principais Etapas da Análise

### 1. Importação e Tratamento de Dados
- Unificação de bases de lojas distintas
- Conversão da coluna `Data da Compra` para datetime(se já não tiver)
- Criação das colunas `Mês` e `Ano`
- Arredondamento de valores de frete
- Padronização numérica com função personalizada

### 2. Análise Exploratória
- Cálculo do faturamento por loja
- Avaliação do valor médio de frete
- Gráficos temporais de faturamento e Média de vendas

### 3. Visualizações Estratégicas
> Gráficos essenciais incluídos no notebook:

- Receita mensal por loja
- Média de vendas mensal
- Evolução do frete
- Comparação entre lojas

---

## 📥 Como Executar

Clone o repositório:

```
git clone https://github.com/Siiqueira/Alura_Store_BR.git
cd AluraStoreBr
```
Abra o Jupyter Notebook:  
```
jupyter notebook AluraStoreBr.ipynb
```
---

📄 Licença
MIT License – Livre para uso, estudo e modificação.

✉️ Contato  
Desenvolvido por Ellan Alves  
- analistaellan@gmail.com
-  [LinkedIn](https://www.linkedin.com/in/ellan-alves-dados/)
