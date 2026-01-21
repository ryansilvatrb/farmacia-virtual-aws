# 💊 Farmácia Virtual na AWS

Este projeto foi desenvolvido como parte de um **Desafio de Projeto da DIO**, com o objetivo de aplicar, na prática, conceitos fundamentais de **Computação em Nuvem utilizando a AWS**.

A proposta consiste em **conceber e projetar uma plataforma virtual para uma farmácia fictícia**, simulando um cenário real de mercado e utilizando serviços da AWS para garantir escalabilidade, segurança e alta disponibilidade.

---

## 🎯 Objetivo do Projeto

Projetar a arquitetura de uma aplicação de **Farmácia Virtual**, contemplando:

* Hospedagem de aplicação web
* Gerenciamento de dados de clientes e produtos
* Segurança da infraestrutura
* Escalabilidade e alta disponibilidade

O foco principal está **na arquitetura em nuvem**, e não no desenvolvimento do código da aplicação.

---

## ☁️ Arquitetura Proposta (AWS)

A arquitetura da solução utiliza os seguintes serviços da AWS:

* **Amazon VPC** – Isolamento e controle da rede
* **Amazon EC2** – Hospedagem da aplicação web
* **Elastic Load Balancer (ALB)** – Distribuição de carga
* **Amazon RDS** – Banco de dados relacional
* **Amazon S3** – Armazenamento de arquivos e imagens
* **AWS IAM** – Controle de permissões e segurança
* **AWS CloudWatch** – Monitoramento da aplicação

O diagrama da arquitetura está disponível na pasta:

```
diagramas/
```

---

## 📂 Estrutura do Repositório

```
farmacia-virtual-aws/
│
├── diagramas/              # Diagramas da arquitetura AWS
│
├── referencias/            # Links e materiais de apoio
│   └── links-aws.md
│
├── README.md               # Documentação do projeto
├── modelo-relatorio.md     # Relatório técnico (entrega DIO)
```

---

## 🧠 Conceitos Aplicados

* Computação em Nuvem
* Infraestrutura como Serviço (IaaS)
* Arquitetura em camadas
* Segurança em ambientes AWS
* Alta disponibilidade
* Escalabilidade

---

## 🧪 Observação Importante

Este projeto é **conceitual e arquitetural**, desenvolvido para fins educacionais. Nenhum serviço AWS foi provisionado de fato, evitando custos reais.

---

## 📚 Referências

Os links oficiais da AWS utilizados como base para o projeto estão disponíveis em:

```
referencias/links-aws.md
```

---

## 👨‍💻 Autor

Projeto desenvolvido por **Ryan Silva** como parte da formação em tecnologia pela **DIO**.
