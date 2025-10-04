# 💳 Análise de Padrões de Pagamento em E-commerce

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![Libs](https://img.shields.io/badge/Libs-Pandas%2C%20Mlxtend-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📖 Sobre o Projeto

Este projeto aplica a técnica de **Análise de Cesta de Compras (Market Basket Analysis)** de uma forma não convencional: em vez de analisar produtos, o foco é descobrir padrões nas **formas de pagamento** utilizadas pelos clientes em um grande e-commerce brasileiro.

O objetivo é identificar quais combinações de meios de pagamento (cartão de crédito, boleto, voucher, etc.) são frequentemente utilizadas em uma mesma transação. A análise utiliza o algoritmo **Apriori** para gerar regras de associação fortes, que revelam o comportamento do consumidor no momento de pagar por suas compras.

Os insights gerados podem ajudar a entender o impacto de campanhas de vouchers, a preferência por parcelamento ou a popularidade de diferentes métodos de pagamento combinados.

## 📦 Dataset Utilizado

O dataset utilizado foi o **"Olist Order Payments Dataset"**, que faz parte do grande conjunto de dados "Brazilian E-Commerce Public Dataset by Olist" disponível no Kaggle. Ele contém dados anonimizados sobre os pagamentos de pedidos realizados na plataforma entre 2016 e 2018.

* **Fonte:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Bibliotecas Principais:**
    * `pandas` para manipulação e preparação dos dados.
    * `mlxtend` para a implementação do algoritmo Apriori e geração das regras de associação.
* **Ambiente:** Jupyter Notebook

## 🚀 Como Executar o Projeto

Siga os passos abaixo para executar a análise em sua máquina local.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/](https://github.com/)[SEU-USUARIO]/analise-padroes-de-pagamento-ecommerce-olist.git
    cd analise-padroes-de-pagamento-ecommerce-olist
    ```

2.  **Crie e ative um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    (Crie um arquivo `requirements.txt` com o conteúdo abaixo)
    ```
    pandas
    mlxtend
    jupyter
    ```
    E depois instale com:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute o Notebook:**
    Abra o Jupyter Notebook e execute o arquivo `analise_pagamentos.ipynb` para ver o passo a passo.
