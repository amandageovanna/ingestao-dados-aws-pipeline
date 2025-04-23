# 🚀 AWS Data Lake: Pipeline para Ingestão de Dados

Este repositório contém o notebook sobre o aprendizado que desenvolvi durante o curso **AWS Data Lake: criando uma pipeline para ingestão de dados**. O objetivo foi construir uma pipeline de ingestão de dados externos, utilizando os principais serviços da AWS voltados para engenharia de dados e governança.

---

## 📌 Objetivo do Projeto

Construir uma pipeline de ingestão de dados baseada na base pública **Data Boston**, utilizando a AWS para estruturar um Data Lake em camadas (Bronze e Silver), garantindo segurança e controle de acesso com boas práticas de cloud.

---

## 🧰 Tecnologias e Ferramentas

- **Amazon S3** – Armazenamento de dados em camadas.
- **Amazon IAM** – Criação de usuários e controle de permissões.
- **AWS Lake Formation** – Governança de dados.
- **AWS Budgets e CloudWatch** – Monitoramento e alertas de custo.
- **Python** – Linguagem para manipulação dos dados.
- **Boto3** – Conexão com serviços AWS.
- **Urllib** – Extração de dados externos via HTTP.
- **BytesIO** – Manipulação de arquivos em memória.
- **Apache Parquet** – Formato de arquivo otimizado.

---

## 🧠 O que foi aprendido

- Criação de conta na AWS com boas práticas de segurança (MFA).
- Criação de alertas de custos para controle financeiro.
- Criação e configuração de usuários IAM.
- Estruturação de um bucket S3 com camadas Bronze e Silver.
- Registro e configuração do Lake Formation.
- Consumo de dados externos com `urllib`.
- Upload de dados em memória com `BytesIO` e `boto3`.
- Escrita dos dados no formato `Parquet` para otimizar performance.
- Diferença entre **Data Warehouse**, **Data Lake** e **Data Lakehouse**.

---
## 📝 Observações

Este projeto é um exercício prático de um curso introdutório, focado em entender os principais serviços da AWS aplicados à ingestão de dados. Apesar de simples, foi essencial para fixar conceitos como o uso de buckets em camadas, permissões com IAM e configurações do Lake Formation, além de treinar o consumo e upload de dados com Python.

---

## ✨ Créditos

Curso: *AWS Data Lake: criando uma pipeline para ingestão de dados*  
Instrutor(a): Ana Hashimoto  
Plataforma: Alura
🔐 As credenciais da AWS são carregadas de variáveis de ambiente para evitar exposição no código. 

---

## 📎 Links Úteis

- 📄 [Base de Dados Data Boston](https://data.boston.gov/dataset/311-service-requests)

---


