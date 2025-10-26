# AWS Architecture — EC2, EBS, S3 & Lambda ☁️

**Desafio do Bootcamp Santander Code Girls – DIO + AWS**

---

## 📘 Descrição

Este projeto tem como objetivo representar uma arquitetura simples de computação em nuvem utilizando serviços da **Amazon Web Services (AWS)**.  
O foco é consolidar o entendimento prático sobre os componentes **EC2**, **EBS**, **S3** e **Lambda**, aplicando os conceitos aprendidos durante o bootcamp.

---

## 🧩 Componentes da Arquitetura

![AWS Architecture](images/arquitetura-drawio.png)

**Fluxo de funcionamento:**

1. **Usuário** acessa a aplicação hospedada na **instância EC2** através de um **Internet Gateway**.  
2. A instância EC2 utiliza um **volume EBS** como armazenamento persistente de dados.  
3. A aplicação pode enviar e recuperar arquivos (imagens, backups) de um **bucket S3**.  
4. Uma **função Lambda** automatiza processos, como mover arquivos ou processar logs, com base em eventos do S3 ou EC2.

---

## ⚙️ Serviços Utilizados

| Serviço | Função |
|----------|--------|
| **EC2 (Elastic Compute Cloud)** | Hospeda a aplicação e processa as requisições dos usuários. |
| **EBS (Elastic Block Store)** | Armazenamento persistente de dados da instância EC2. |
| **S3 (Simple Storage Service)** | Armazenamento de objetos, arquivos e backups. |
| **Lambda Function** | Execução de código automatizado em resposta a eventos. |
| **Internet Gateway** | Permite que o tráfego da internet chegue até o EC2. |

---

## 🧠 Aprendizados

- Entendimento dos principais serviços da AWS e suas interconexões.
- Criação de diagramas arquiteturais usando **Draw.io**.
- Documentação técnica clara em **Markdown (GitHub)**.
- Princípios de **infraestrutura escalável e serverless**.

---

## 📁 Estrutura do Repositório

aws-architecture-dio/
│
├── README.md
├── /images
│ └── arquitetura-drawio.png
└── /diagram
└── arquitetura.drawio

## 👩‍💻 Autora

**Alexia Rodrigues Campos Luz**  
Desenvolvedora Back-End | Entusiasta em Cloud & IA ☁️  
🔗 [LinkedIn](https://www.linkedin.com/in/alexia-luz)  
📚 Bootcamp Santander Code Girls – DIO