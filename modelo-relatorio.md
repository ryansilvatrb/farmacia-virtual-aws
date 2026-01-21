# 📄 Relatório do Projeto – Farmácia Virtual na AWS

## 📌 Introdução

Este projeto foi desenvolvido como parte de um desafio prático da DIO, com o objetivo de aplicar conceitos fundamentais de **Computação em Nuvem utilizando a AWS**. A proposta consiste em conceber e projetar a arquitetura de uma **plataforma virtual para uma farmácia fictícia**, simulando um cenário real do mercado.

O projeto não envolve implementação de código em produção, mas sim o **planejamento arquitetural**, a escolha correta dos serviços AWS e a justificativa técnica dessas decisões.

---

## 🎯 Objetivo do Projeto

Projetar uma arquitetura em nuvem escalável, segura e altamente disponível para uma farmácia virtual, permitindo:

- Hospedagem de uma aplicação web
- Separação de camadas (frontend, backend e banco de dados)
- Alta disponibilidade
- Segurança dos dados
- Escalabilidade conforme a demanda

---

## 🏗️ Arquitetura Proposta

A arquitetura da Farmácia Virtual foi desenhada seguindo boas práticas da AWS, utilizando múltiplos serviços integrados.

### Visão Geral da Arquitetura:
- Usuários acessam a aplicação via internet
- O tráfego é direcionado para a camada de aplicação
- A aplicação se comunica com o banco de dados de forma segura
- Todos os recursos estão isolados em uma VPC

---

## ☁️ Serviços AWS Utilizados

### 🔹 Amazon VPC
Responsável por criar uma rede virtual isolada, garantindo controle de tráfego, segurança e segmentação entre os recursos.

### 🔹 Amazon EC2
Utilizado para hospedar a aplicação web da farmácia, permitindo flexibilidade e controle sobre o ambiente de execução.

### 🔹 Elastic Load Balancer (ELB)
Distribui o tráfego entre múltiplas instâncias EC2, garantindo alta disponibilidade e tolerância a falhas.

### 🔹 Auto Scaling Group
Permite escalabilidade automática das instâncias EC2 conforme a demanda de acesso à aplicação.

### 🔹 Amazon RDS
Banco de dados relacional utilizado para armazenar informações como usuários, produtos e pedidos, com recursos de backup, failover e alta disponibilidade.

### 🔹 Security Groups
Utilizados como firewall virtual para controlar o tráfego de entrada e saída das instâncias e do banco de dados.

---

## 🔐 Segurança

A segurança foi considerada em todas as camadas da arquitetura:

- Uso de **Security Groups** para restringir acessos
- Banco de dados isolado em sub-rede privada
- Separação entre camada pública e privada
- Controle de acesso baseado em regras específicas

---

## 📈 Escalabilidade e Disponibilidade

- **Auto Scaling** garante crescimento ou redução automática dos recursos
- **Load Balancer** evita ponto único de falha
- Uso de **Zonas de Disponibilidade** para maior resiliência
- Arquitetura preparada para picos de acesso

---

## 🧠 Conceitos Aplicados

- Computação em Nuvem
- Infraestrutura como Serviço (IaaS)
- Alta Disponibilidade
- Escalabilidade Horizontal
- Segurança em Nuvem
- Arquitetura em Camadas
- Boas práticas AWS

---

## 🤖 Uso de Inteligência Artificial no Desenvolvimento

Este projeto contou com o **auxílio de Inteligência Artificial (ChatGPT)** para:

- Organização da arquitetura
- Explicação dos serviços AWS
- Escrita e estruturação da documentação
- Clareza técnica e didática do relatório

O uso de IA teve caráter **educacional e de apoio**, não substituindo o aprendizado, mas acelerando a compreensão e a qualidade do material entregue.

---

## ✅ Conclusão

O projeto da Farmácia Virtual permitiu consolidar conceitos essenciais de AWS e arquitetura em nuvem, aproximando o aprendizado teórico de um cenário real do mercado. A solução proposta é escalável, segura e alinhada às boas práticas recomendadas pela AWS, cumprindo plenamente os objetivos do desafio.

---

📌 **Projeto desenvolvido para fins educacionais no âmbito da plataforma DIO.**
