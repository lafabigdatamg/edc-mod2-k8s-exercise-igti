<p align="center">
  <a href="" rel="noopener">
 <img width=210px height=200px src="https://media-exp1.licdn.com/dms/image/C4D0BAQG7OjFosqn9dA/company-logo_200_200/0/1625776698161?e=2159024400&v=beta&t=1yvuOj8Q0MbxulP1hEfwjY5U55aU8VdBW77FNJISzpI" alt="Project logo"></a>
</p>

<h3 align="center">Bootcamp Engenheiro(a) de Dados Cloud - IGTI - Módulo 2</h3>

<div align="center">

## TRABALHO PRÁTICO DO MÓDULO 2 DO BOOTCAMP ENGENHARIA DE DADOS CLOUD IGTI 2022

### Objetivos
- Utilizar os principais serviços de nuvem para Engenharia de Dados;
- Utilizar o Kubernetes como Gerenciador de Containers;
- Ingerir dados em real time no Apache Kafka;
- Implementar um pipeline de processamento de Big Data em real time;
- Realizar Processamento de dados utilizando Ksqldb;
- Disponibilizar dados no Apache Pinot.

### Enunciado

Você é Engenheiro(a) de Dados e precisa realizar a migração de uma tabela relacionada a clientes, 
que é altamente requisitada pela área de negócios para, assim, realizar análises comportamentais 
dos clientes. O gestor de sua área iniciou um projeto de migração para que esses dados sejam 
disponibilizados em tempo real, e você será responsável por construir uma pipeline em real time
para disponibilizar esses dados no DW. Você precisará realizar o processamento utilizando 
ferramenta adequada e disponibilizar o dado para consultas dos usuários de negócios e analistas de 
BI.Para a realização desta atividade, recomenda-se o uso dos serviços AWS.

### Atividades

1. Crie um RDS Postgres que tenha acesso público liberado;
2. Clonar o projeto https://github.com/carlosbpy/igti-k8s-exercise;
3. Ingerir dados da tabela de customers para o postgres;
4. Deployar EKS na AWS ou utilizar o Minikube;
5. Migrar tabela de customers para a estrutura do Kafka;
6. Realizar o processamento dos dados da tabela de customers utilizando o KsqlDB;
7. Disponibilizar dados da tabela de customers em real time para o Apache Pinot.