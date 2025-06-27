# 🎯 Criando Instâncias Gerenciadas de SQL do Azure

Este repositório tem como objetivo demonstrar, de forma prática e didática, como criar uma **Instância Gerenciada de SQL** no **Microsoft Azure**. É indicado para estudantes, profissionais de TI, desenvolvedores e entusiastas que desejam aprender a provisionar, configurar e gerenciar bancos de dados em nuvem utilizando a plataforma Azure.

---

## ✅ Objetivo

- Criar uma **Instância Gerenciada de SQL** no Azure.
- Demonstrar o passo a passo com imagens e comandos.
- Compartilhar boas práticas de segurança e configuração.

---

## 🔧 Pré-requisitos

Antes de iniciar, é necessário ter:

- ✅ Conta ativa no **Microsoft Azure** (pode ser uma conta gratuita).
- ✅ Acesso ao **Portal Azure**.
- ✅ Permissão para criar recursos no Azure.

---

## 🚀 Passo a Passo

### 1️⃣ Acesse o Portal Azure

1. Acesse [https://portal.azure.com](https://portal.azure.com)  
2. Faça login com sua conta Microsoft.

---

### 2️⃣ Crie um Grupo de Recursos

1. No menu lateral, clique em **Grupos de Recursos**.
2. Clique em **Adicionar**.
3. Defina:
   - **Assinatura:** Sua assinatura ativa.
   - **Nome do grupo de recursos:** Por exemplo, `rg-sql-managed`.
   - **Região:** Escolha a região mais próxima.
4. Clique em **Revisar + criar** > **Criar**.

---

### 3️⃣ Crie a Instância Gerenciada de SQL

1. No menu de pesquisa, digite **Instância Gerenciada de SQL**.
2. Clique em **Instâncias Gerenciadas de SQL** > **Criar**.
3. Preencha as informações:
   - **Assinatura:** Sua assinatura.
   - **Grupo de recursos:** `rg-sql-managed`.
   - **Nome da instância:** Por exemplo, `sql-managed-demo`.
   - **Região:** Mesma da do grupo de recursos.
   - **Nome do administrador:** Escolha um nome de usuário.
   - **Senha:** Defina uma senha forte.
4. Clique em **Avançar: Rede**.

---

### 4️⃣ Configuração de Rede

1. Escolha ou crie uma **Rede Virtual**.
2. Configure as **Sub-redes** conforme necessário.
3. Configure o **Endpoint Público**, se desejar permitir conexões externas (opcional e não recomendado para produção).

---

### 5️⃣ Revisar e Criar

1. Revise todas as configurações.
2. Clique em **Criar**.
3. Aguarde o provisionamento da instância (pode levar alguns minutos).

---

### 6️⃣ Conectar à Instância

1. Após a criação, vá para a instância criada.
2. Anote o **Nome DNS**.
3. Use uma ferramenta como **Azure Data Studio** ou **SQL Server Management Studio (SSMS)** para se conectar.
4. Autentique usando o usuário e senha definidos.

---

## 🔒 Boas Práticas de Segurança

- Utilize **Firewall** para limitar o acesso.
- Habilite **Autenticação Multifator** na sua conta Azure.
- Mantenha as senhas fortes e atualizadas.
- Realize backups periódicos.
- Monitore o desempenho com **Azure Monitor**.

---

## 📚 Referências

- [Documentação Oficial do Azure SQL Managed Instance](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/sql-managed-instance-overview)
- [Portal Azure](https://portal.azure.com)
- [Azure Data Studio](https://learn.microsoft.com/pt-br/sql/azure-data-studio/)

---

## 📌 Observações

Este repositório é de caráter **educacional** e não deve ser usado para produção sem as devidas adaptações de segurança e configuração.

---

## 📝 Licença

Este projeto está licenciado sob a Licença MIT.

---

## 🙌 Autor

Este repositório foi criado por Gisely Oliveira para fins de estudo e demonstração de uso do **Microsoft Azure**.

---
