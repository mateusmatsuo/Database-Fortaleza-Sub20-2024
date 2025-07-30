# Database-Fortaleza-Sub20-2024

Este projeto foi desenvolvido como desafio proposto pelo curso "Python para Futebol" da Footure Academy, e tem como objetivo a construção de uma base de dados com informações dos jogadores do time Sub-20 do Fortaleza, utilizando técnicas de web scraping para a coleta dos dados, e estrutura de dados aninhada (lista de dicionários) para o armazenamento desses dados. Os dados estatísticos coletados dos jogadores são referentes ao Brasileirão Sub-20 de 2024.

## 📌 Objetivo

O objetivo principal do projeto é coletar dados dos jogadores do Fortaleza Sub-20 a partir de fontes públicas (site OGol) e organizar essas informações em uma estrutura de dados adequada, exportando posteriormente para **CSV** e, assim, deixando pronto para análises futuras.

## ⚙️ Funcionalidades implementadas

- Coleta automática dos links dos jogadores a partir da página do elenco.
- Extração individual de dados pessoais e estatísticos da página de cada jogador.
- Armazenamento dos dados em uma **lista de dicionários**.
- Exportação da base final para arquivo **CSV**.

## 🌐 Estrutura dos dados

Cada jogador é representado como um dicionário com os seguintes campos:

`nome`, `idade`, `nacionalidade`, `posicao`, `pe_dominante`, `altura_cm`, `peso_kg`, `partidas_jogadas`, `minutos_jogados`, `gols_marcados`, `gols_sofridos` e `assistencias`

## ▶️ Como executar o projeto

Siga os passos abaixo para executar o projeto localmente:

### 1. Clone o repositório

```bash
git clone https://github.com/mateusmatsuo/Database-Fortaleza-Sub20-2024.git
cd Database-Fortaleza-Sub20-2024
```

### 2. Instale as dependências necessárias

```bash
pip install requests beautifulsoup4 csv
```

### 3. Execute o Notebook

Abra o arquivo `desafio01.ipynb` em um ambiente Jupyter ou Google Colab e execute as células passo a passo.

### 4. Verifique o arquivo CSV gerado

Ao final, será gerado o arquivo `jogadores_fortaleza_sub20.csv` contendo a base de dados com os jogadores da equipe Sub-20 do Fortaleza.

Você pode abrir este arquivo em qualquer editor de planilhas (como Excel ou Google Sheets) ou até mesmo utilizar o pandas.
