# Projeto Alura: Análise de Vendas de Quatro Lojas

**Exploração de dados em Python para recomendar a Loja 3 ao Sr. João**

&#x20;  &#x20;

---

## 🔍 Introdução

Este repositório apresenta uma **Análise Exploratória de Dados** das vendas de quatro lojas, com o objetivo de ajudar o **Sr. João** a escolher em qual delas vender seus produtos. A partir de informações de faturamento, avaliações de clientes e custo de frete, identificamos que a **Loja 3** é a mais promissora.

## 🚀 Tecnologias

* **Python 3.8+**
* **Pandas** – Manipulação e análise de dados
* **NumPy** – Suporte a operações matemáticas
* **Matplotlib** – Criação de gráficos
* **Seaborn** – Visualizações estatísticas
* **Matplotlib.ticker.FuncFormatter** – Formatação personalizada de eixos

## 📁 Estrutura do Repositório

```
Projeto_alura/
├── Alurav2.ipynb       # Notebook com todo o workflow de análise
├── data/               # Arquivos de dados brutos (CSV, Excel, etc.)
├── assets/             # Imagens e gráficos gerados
│   └── faturamento_lojas.png
├── requirements.txt    # Dependências do projeto
└── LICENSE             # Licença MIT
```

## ⚙️ Como Rodar

1. Clone o repositório:

   ```bash
   ```

git clone [https://github.com/crgolart12/Projeto\_alura.git](https://github.com/crgolart12/Projeto_alura.git) cd Projeto\_alura



2. Instale as dependências:

   ```bash
   ```

pip install -r requirements.txt

````
4. Abra o notebook no Jupyter:
   ```bash
jupyter notebook Alurav2.ipynb
````

## 📊 Resultados e Conclusão

A análise apresentou o faturamento das lojas de 2020 a 2023 e levou em conta:

* Faturamento total anual
* Crescimento percentual (2020–2022)
* Avaliação média dos clientes
* Produtos mais e menos vendidos
* Custo médio de frete

| Loja       | 2020              | 2021              | 2022              | 2023              | % Cresc. 2020–22 |
| ---------- | ----------------- | ----------------- | ----------------- | ----------------- | ---------------- |
| Loja 1     | R\$ 40.000,00     | R\$ 25.000,00     | R\$ 27.000,00     | R\$ 30.000,00     | –32,5%           |
| Loja 2     | R\$ 30.000,00     | R\$ 32.000,00     | R\$ 50.000,00     | R\$ 20.000,00     | +66,7%           |
| **Loja 3** | **R\$ 33.433,43** | **R\$ 40.000,00** | **R\$ 57.256,82** | **R\$ 31.538,81** | **+71,4%**       |
| Loja 4     | R\$ 35.000,00     | R\$ 36.000,00     | R\$ 34.000,00     | R\$ 25.000,00     | –2,9%            |

> **Recomendação:** A **Loja 3** se destaca por seu crescimento consistente e desempenho acima da média, sendo a melhor opção para o Sr. João expandir suas vendas.

### Gráfico de Faturamento

## 📎 Links Úteis

* Notebook no NBViewer: [https://nbviewer.org/github/crgolart12/Projeto\_alura/blob/main/Alurav2.ipynb](https://nbviewer.org/github/crgolart12/Projeto_alura/blob/main/Alurav2.ipynb)
* Imagem do gráfico: `assets/faturamento_lojas.png`

![faturamento_lojas](https://github.com/user-attachments/assets/b226ab6d-c55f-41ed-a2db-cd18b2ea0ddb)


## 📝 Licença

Este projeto está licenciado sob a **Licença MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


