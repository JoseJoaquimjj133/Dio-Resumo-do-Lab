# Introdução ao Microsoft Azure ☁️

O **Microsoft Azure** é a plataforma de computação em nuvem da Microsoft, projetada para construir, implantar e gerenciar aplicativos e serviços por meio de uma rede global de datacenters. Ele oferece uma ampla variedade de soluções como máquinas virtuais, bancos de dados, armazenamento, redes, inteligência artificial, DevOps, segurança e muito mais.

Com o Azure, desenvolvedores e empresas podem escalar suas aplicações de forma rápida e segura, aproveitando modelos de computação como IaaS (Infraestrutura como Serviço), PaaS (Plataforma como Serviço) e SaaS (Software como Serviço). Além disso, o Azure é altamente integrado com ferramentas populares como GitHub, Visual Studio, Power BI e Active Directory, facilitando o desenvolvimento e a gestão de soluções completas.

Seja você um iniciante em nuvem ou um arquiteto experiente, o Azure oferece ferramentas poderosas e flexíveis para transformar ideias em soluções reais.

---

> **Principais recursos do Azure:**
> - Computação (VMs, App Services, Functions)
> - Armazenamento (Blob, File, Queue, Table)
> - Banco de dados (SQL, Cosmos DB, PostgreSQL, MySQL)
> - Redes (VNet, Load Balancer, VPN)
> - Inteligência artificial e machine learning
> - Segurança e conformidade
> - Integração com DevOps e CI/CD

Para saber mais, acesse a [documentação oficial do Azure](https://learn.microsoft.com/azure/).

# 📘 Resumo do Microsoft Azure

Este manual fornece um guia introdutório sobre como utilizar os principais recursos do **Microsoft Azure**, incluindo a criação de máquinas virtuais, instâncias de banco de dados, redes virtuais e práticas de segurança.

---

## 🔹 1. Criação de Máquinas Virtuais (VMs)

### Passos:
1. Acesse o portal: [https://portal.azure.com](https://portal.azure.com)
2. Vá em **"Máquinas Virtuais"** > **“+ Criar”** > **“Máquina Virtual”**
3. Preencha os dados:
   - Grupo de Recursos
   - Nome da VM
   - Região (ex: Brazil South)
   - Imagem (ex: Ubuntu, Windows Server)
   - Tamanho da máquina (CPU/RAM)
   - Tipo de autenticação (senha ou chave SSH)
4. Escolha os discos
5. Configure a rede (usar ou criar uma VNet)
6. Clique em **Revisar + Criar**

---

## 🔹 2. Criação de Recursos no Azure

### O que são:
Recursos no Azure incluem VMs, bancos de dados, redes, armazenamento, entre outros.

### Como criar:
1. Clique em **“Criar um recurso”**
2. Escolha a categoria (ex: Computação, Banco de Dados)
3. Siga as etapas do assistente de configuração

---

## 🔹 3. Criação de Instâncias de Banco de Dados

### Opções disponíveis:
- Azure SQL Database
- MySQL / PostgreSQL / MariaDB gerenciados
- Cosmos DB (NoSQL)

### Exemplo (Azure SQL):
1. Criar recurso > **SQL Database**
2. Defina:
   - Nome do banco
   - Grupo de recursos
   - Servidor (crie um se necessário)
   - Performance (DTU ou vCore)
3. Configure backups e redundância
4. Clique em **Criar**

---

## 🔹 4. Configuração de VNet (Virtual Network)

### O que é:
Uma rede virtual privada no Azure que permite comunicação entre recursos.

### Como criar:
1. Vá para **"Rede Virtual"** > **+ Criar**
2. Configure:
   - Nome da VNet
   - Intervalo de IPs (ex: 10.0.0.0/16)
   - Sub-redes (ex: 10.0.1.0/24)
3. Defina opções de segurança e clique em **Criar**

---

## 🔹 5. Segurança no Azure

### Boas práticas:
- **Azure Active Directory (AAD)**: controle de identidade
- **NSG (Network Security Group)**: regras de tráfego
- **Key Vault**: armazenamento seguro de segredos e chaves
- **Azure Security Center**: monitoramento e recomendações de segurança
- **MFA (Multi-Factor Authentication)**: proteção de acesso
- **RBAC (Role-Based Access Control)**: controle de permissões por função

---

## 📎 Recursos úteis
- [Documentação oficial Azure](https://learn.microsoft.com/pt-br/azure/)
- [Azure CLI](https://learn.microsoft.com/pt-br/cli/azure/)
- [Calculadora de preços Azure](https://azure.microsoft.com/pt-br/pricing/calculator/)

---

> _Este guia é voltado para iniciantes e estudantes que desejam entender e começar a trabalhar com a plataforma Azure._

