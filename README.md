# ☁️ Desafio DIO – Gerenciamento de Instâncias EC2 na AWS

## 📘 Descrição do Projeto
Este repositório documenta a prática realizada durante o desafio da DIO sobre **gerenciamento de instâncias EC2 na AWS**.  
O objetivo foi aplicar conceitos aprendidos sobre instâncias EC2, otimização de recursos e armazenamento na nuvem, criando um registro técnico detalhado da experiência.

---

## 🎯 Objetivos de Aprendizagem
- Compreender os conceitos e tipos de **instâncias EC2**.  
- Aplicar técnicas de **otimização de recursos** na nuvem.  
- Entender o uso de **armazenamento EBS e S3**.  
- Documentar processos técnicos no GitHub para estudo e portfólio.  

---

## ⚙️ Conceitos Aplicados

### 1️⃣ O que são Instâncias EC2
As **instâncias EC2 (Elastic Compute Cloud)** são servidores virtuais na nuvem da AWS que permitem executar aplicações sob demanda.  
Durante o desafio, aprendemos a:
- Criar e configurar instâncias EC2;
- Conectar via **SSH**;
- Controlar permissões com **Security Groups**.

### 2️⃣ Tipos de Instâncias EC2
A AWS oferece diferentes tipos de instâncias, escolhidas de acordo com a **necessidade de CPU, memória e armazenamento**.  
Exemplos utilizados durante o desafio:
- **t2.micro** – ideal para testes e Free Tier.  
- **t3.small / t3.medium** – para aplicações com mais recursos.  

### 3️⃣ Otimização de Recursos
- Monitoramento do uso de CPU e memória.  
- Escolha de tipos de instância compatíveis com a carga da aplicação.  
- Parada ou encerramento de instâncias quando não utilizadas, para **reduzir custos**.

### 4️⃣ Armazenamento na Nuvem
#### Amazon EBS
- **Elastic Block Store (EBS)** é usado como disco virtual das instâncias EC2.  
- Permite criar **volumes persistentes** que permanecem mesmo após desligar a instância.  

#### Amazon S3
- **Simple Storage Service (S3)** é usado para armazenar arquivos de forma **escalável e segura**.  
- Pode ser integrado para **armazenamento de dados e backup**.  
- Suporta versionamento e Lifecycle para **reduzir custos automaticamente**.

---

## ⚡ Etapas Realizadas
1. Login no **AWS Management Console** e acesso ao serviço **EC2**.  
2. Criação de uma instância EC2 **t2.micro**, configuração de **Security Group** e **par de chaves**.  
3. Conexão via SSH e instalação de pacotes básicos.  
4. Teste de funcionamento e monitoramento de métricas.  
5. Integração com armazenamento:
   - EBS: criação de volume adicional e anexação à instância.  
   - S3: criação de bucket para armazenar arquivos e backups.  
6. Parada e encerramento seguro da instância para evitar cobranças desnecessárias.  

---

## 💡 Insights e Aprendizados
Durante a prática, pude compreender melhor:

- Como a AWS oferece **infraestrutura sob demanda**.  
- A importância de **escolher o tipo de instância** certo para cada necessidade.  
- O processo de **acesso remoto via SSH** e o uso de chaves privadas.  
- Como **EBS e S3 complementam a instância** para armazenamento persistente e escalável.  
- A importância de **otimizar recursos e controlar custos** na nuvem.

---

## 🧩 Tecnologias Utilizadas
- **AWS EC2, EBS, S3**  
- **Git e GitHub**

---

## 📎 Referências
- [Documentação AWS EC2](https://docs.aws.amazon.com/pt_br/ec2/index.html)  
- [Documentação AWS EBS](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/ebs.html)  
- [Documentação AWS S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)  
- [Digital Innovation One (DIO)](https://www.dio.me/)  

---

## 👩‍💻 Autor
Desenvolvido por **Silvia Toledo**  
📚 Desafio da Formação **Cloud AWS Practitioner** na **DIO**  
🔗 [Meu Perfil no GitHub](https://github.com/silviatoledo1308-jpg)

