# sentiment_analysis - Aplicativo de Análise de Sentimentos

## 📖 Sobre
**Sentiment_analysis** é uma aplicação Java utilizando **Spring Boot** e **RestTemplate** para fornecer uma API RESTful de análise de sentimentos. O backend interage com um microserviço Python para prever o sentimento (positivo, negativo, neutro) de um texto fornecido. A API pode ser utilizada para analisar sentimentos de qualquer texto enviado via **POST**, e também permite consultar, atualizar e excluir previsões de sentimentos com base em um **ID**.

Este projeto foi desenvolvido por **Marco Antônio** para demonstrar como integrar Spring Boot com um microserviço Python para análise de sentimentos, proporcionando uma maneira simples e eficaz de integrar análise de texto em aplicações web.

## 🚀 Tecnologias

<div>
  <img src="https://img.shields.io/badge/Java-17-blue?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Boot-3.0.6-green?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/RestTemplate-42.5.6-blue?style=for-the-badge&logo=postman&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
</div>

<p>Este projeto utiliza as seguintes tecnologias:</p>
<ul>
  <li><strong>Java</strong>: Linguagem de programação usada para o backend da aplicação.</li>
  <li><strong>Spring Boot</strong>: Framework Java utilizado para criar a API do sistema.</li>
  <li><strong>RestTemplate</strong>: Classe do Spring usada para enviar requisições HTTP e consumir o microserviço Python de análise de sentimentos.</li>
  <li><strong>Python</strong>: Linguagem usada no microserviço para realizar a análise de sentimentos.</li>
  <li><strong>Flask</strong>: Framework Python utilizado para criar o microserviço RESTful de análise de sentimentos.</li>
</ul>

## 📊 Estado do Projeto

![Progresso](https://img.shields.io/badge/Progresso-100%25-green?style=for-the-badge&labelColor=000000&color=008000&logo=github)

> O projeto está completo e funcionando perfeitamente, com todos os endpoints em produção.

##  Autor
<h2>Marco Antônio</h2>

<p>Desenvolvedor Backend</p>

<p>
  <a href="https://github.com/marcosynky" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
<a href="https://www.linkedin.com/in/marco-antônio-developer-backend" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

</p>

## 📱 Funcionalidades

- **Análise de Sentimentos**: Realiza a análise de sentimentos de um texto enviado via **POST**.
- **Consulta de Previsões**: Busca de uma previsão de sentimento com base no **ID**.
- **Atualização de Previsões**: Atualização de uma previsão existente de sentimento.
- **Exclusão de Previsões**: Exclusão de uma previsão de sentimento com base no **ID**.
- **Previsão Padrão**: Caso o microserviço Python falhe ou não retorne uma previsão válida, o sistema retorna uma previsão padrão.

## 🛠️ Como Rodar o Projeto

### Pré-requisitos

1. **Java 17**: Verifique se o **Java** está instalado corretamente no seu sistema.
   - Instalação do Java: [Java Docs](https://docs.oracle.com/en/java/javase/17/)
   
2. **Spring Boot**: O projeto foi desenvolvido com **Spring Boot 3.0.6**.
   - Instalação do Spring Boot: [Spring Boot Docs](https://spring.io/projects/spring-boot)

3. **Python e Flask**: É necessário configurar o microserviço Python que realiza a análise de sentimentos. O microserviço foi criado com **Flask**.
   - Instalação do Python: [Python Docs](https://www.python.org/downloads/)
   - Instalação do Flask: 
     ```bash
     pip install Flask
     ```

### Passos para rodar o projeto

1. Clone o repositório para sua máquina local:

```bash
git clone https://github.com/marcosynky/sentiment_analysis.git
cd sentiment_analysis
