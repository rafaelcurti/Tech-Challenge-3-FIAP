# Tech Challenge – Fase 3  
## Banco de Dados e Modelagem das Bases com Databricks

Este projeto tem como objetivo realizar a modelagem e análise de dados da pesquisa **PNAD COVID-19** do IBGE, utilizando a plataforma **Databricks Community Edition** para processamento e estruturação dos dados em nuvem.

---

## 📌 Objetivo

- Preparar uma base de dados limpa, estruturada e modelada para análise da pandemia da COVID-19.
- Trabalhar com arquivos de diferentes meses da PNAD COVID-19.
- Criar tabelas dimensões e fato.
- Selecionar e analisar variáveis demográficas, clínicas, comportamentais e econômicas da população brasileira.

---

## 🧠 Sobre o Databricks

O **Databricks** é uma plataforma de computação em nuvem criada por engenheiros que desenvolveram o **Apache Spark**. Permite o uso de clusters para processar grandes volumes de dados de forma distribuída, além de oferecer suporte para notebooks interativos em Python, SQL, R e outros.

---

## 🗂️ Estrutura do Projeto

### 📁 Bases utilizadas
- PNAD COVID-19 - IBGE
- Meses selecionados: **Julho, Agosto e Setembro de 2020**

### 📊 Modelagem
- **Tabela Fato**: contém dados principais para análise.
- **Tabelas Dimensão**: 
  - Dim_UF: informações dos estados.
  - Dim_Perguntas: metadados das perguntas.

---

## 🧩 Variáveis selecionadas

### 👤 Variáveis demográficas
- A002 – Idade do morador  
- A003 – Sexo  
- A004 – Cor ou raça  
- A005 – Escolaridade  
- V1022 – Situação do domicílio  
- V1023 – Tipo de área  

### 🤒 Sintomas e Saúde
- B0011 – Teve febre?  
- B0012 – Teve tosse?  
- B0013 – Teve dor de garganta?  
- B0015 – Teve dor de cabeça?  
- B00111 – Perda de cheiro ou sabor  
- B002 – Procurou estabelecimento de saúde  
- B0033/B0034 – Uso de medicamentos  
- B007 – Possui plano de saúde  
- B0101 a B0104 – Diagnóstico de doenças crônicas  
- B011 – Resultado do teste COVID-19  

### 🧼 Itens de proteção e higiene
- F002A1 – Sabão/detergente  
- F002A2 – Álcool 70%  
- F002A3 – Máscaras  
- F002A5 – Água sanitária/desinfetante  

### 💼 Trabalho
- C007C – Tipo de trabalho/cargo exercido  

---

## ☁️ Tecnologias utilizadas

- **Databricks Community Edition**
- **Apache Spark**
- **Python / PySpark**
- **DBFS (Databricks File System)**
- **Google Drive / GitHub (para versionamento)**

---

## 🧪 Como executar

1. Faça upload dos arquivos `.csv` para o Databricks, no caminho `/FileStore/tables/`.
2. Configure um cluster (mínimo: 1 nó, Databricks Runtime 11+).
3. Execute o notebook `Tech Challenge - Fase 3 - BD e Modelagem das Bases.ipynb`.
4. As tabelas serão estruturadas no formato de modelo dimensional (fato/dimensões).

---

## 📷 Imagens do projeto

### Upload das bases:
![bases]([https://path-para-sua-imagem/BASES.jpg](https://github.com/rafaelcurti/Tech-Challenge-3-FIAP/blob/main/BASES.jpg))

### Cluster criado:
![cluster]([https://path-para-sua-imagem/Cluster.jpg](https://github.com/rafaelcurti/Tech-Challenge-3-FIAP/blob/main/Cluster.jpg))

---

## ✍️ Autores

- Luciana May
- Paloma Cristina Pinheiro
- Ozir José Azevedo Júnior
- Rafael Curti Barros
- Rilciane de Sousa Bezerra

---

## 📌 Observações

- Projeto desenvolvido como parte do **Tech Challenge** da pós-graduação.
- Foco na criação de uma base estruturada para futuras análises com BigQuery, dashboards, e outros.

