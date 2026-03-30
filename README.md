# 🛍️ E-Sale
## 📌 Sobre o projeto

Projeto criado com o intúito de aprofundar meus conhecimentos em arquitetura de 𝗺𝗶𝗰𝗿𝗼𝘀𝘀𝗲𝗿𝘃𝗶ç𝗼𝘀 utilizando o ecossistema
𝗝𝗮𝘃𝗮 com Spring Boot. A proposta foi desenvolver um sistema de e-commerce dividido em múltiplos serviços independentes,
permitindo explorar na prática conceitos importantes de arquitetura distribuída.

O sistema foi estruturado em diferentes microsserviços responsáveis por domínios específicos da aplicação, como
clientes, produtos, vendas e pagamentos. Cada serviço possui sua própria responsabilidade e lógica de negócio, seguindo
o princípio de separação de responsabilidades, comum em arquiteturas de microsserviços. Esse modelo permite que cada
serviço seja desenvolvido, mantido e escalado de forma independente.

Durante o desenvolvimento do projeto, foram exploradas diversas tecnologias e práticas utilizadas em aplicações modernas, como:

- 🧠 Miro para idealização e fluxos
- 📊 GitHub Projects para gerenciamento
- 🌱 Spring Boot para criação dos microserviços
- 📄 Swagger para documentação das APIs
- 🔗 OpenFeign para realizações de requisições HTTP
- 📡 Apache Kafka para mensageria entre os microserviços
- 🐳 Docker para conteinerização
- 💳 Mercado Pago para pagamentos
- 🍃 MongoDB para armazenamento dos dados
- ☁️ AWS para notificação dos processos da compra realizada

Esse processo permitiu compreender melhor desafios de sistemas distribuídos, como:

- 🔄 Comunicação entre serviços
- ⚠️ Tratamento de falhas
- 🧩 Organização da lógica de negócio

Além disso, o projeto foi pensado como um ambiente de aprendizado e experimentação, permitindo aplicar na prática conceitos de:

- 🏗️ Arquitetura de software
- 📡 Mensageria
- ⚙️ Backend
- 📚 Boas práticas

🔗 O projeto também está postado no [LinkedIn](www.linkedin.com/in/jobson-de-oliveira)

## 🗺️ Mapeamento do sistema no Miro

[👉 Acessar diagrama](https://miro.com/welcomeonboard/WDd5bTU0KzA5eGNUY0dpMlRncU05V0pDendOQzlHUXVJZ2k4aUtWT2JyRm1tTVU2Q1F1VUNpNkJPRFlUYWVLZldTK1BXQnNId2N2NXZWeDVJc2hxR0pNM0VWNjh4QnovbGlSSGphRTJsdUt3QWVUSExjdkVGSnJmSWtOV0ZKczhzVXVvMm53MW9OWFg5bkJoVXZxdFhRPT0hdjE=?share_link_id=666215258423)

![E-Sale - Main flow (Make a sale and delivery the products) (2)](https://github.com/user-attachments/assets/53d2e42c-4d01-448b-854d-5d117b4b1177)

![E-Sale - Cancel a sale (1)](https://github.com/user-attachments/assets/726eb8a7-fa73-42d4-b659-8cb841d37170)

## 📋 Gerenciamento do projeto (Kanban)

![2026-03-19 19-47-50](https://github.com/user-attachments/assets/6455382d-e583-42d4-8c2c-e28d4a297687)

## 🛠️ Ferramentas Utilizadas

- ☕ Java 17
- 🌱 Spring Boot
- 📦 Maven
- 🔗 OpenFeign
- 🍃 MongoDB
- 📡 Apache Kafka
- 📄 Swagger
- 🐳 Docker
- 🔧 Git
- 🌐 GitHub
- 📊 GitHub Projects
- 🧠 Miro
- 🧪 Postman
- 💳 Mercado Pago (API)
- 💻 IntelliJ IDEA

## 🧩 Microserviços

- [👤 Client](https://github.com/JobsonDeveloper/Client-Microservice)
- [📦 Product](https://github.com/JobsonDeveloper/Product-Microservice)
- [💰 Sale](https://github.com/JobsonDeveloper/Sale-Microservice)
- [💳 Payment](https://github.com/JobsonDeveloper/Payment-Microservice)

## 🚀 Como testar

1. 📥 Faça um fork dos microserviços citados acima
2. 🐳 Suba os containers:
```
docker compose up --build
```
3. 📥 Faça um fork deste projeto e suba o Kafka e o MongoDB:
```
docker compose up -d
```
4. 🌐 Acesse a documentação das APIs:
```
http://localhost:(8082,8083,8084 ou 8085)/swagger-ui/index.html
```
