# 📘 Estudos sobre Microsoft Azure – Banco de Dados

Este repositório contém resumos, anotações e dicas práticas sobre o uso da plataforma Microsoft Azure, com foco no processo de criação e configuração de uma instância de Banco de Dados.
O objetivo é servir como material de apoio para estudos, organizando informações essenciais para consulta rápida e fixação dos conceitos.

---

## 🚀 Configuração de uma Instância de Banco de Dados no Azure
### 1️⃣ Acesso ao Portal
Entre no Portal do Azure
Use sua conta Microsoft ou a fornecida pela instituição/empresa.

### 2️⃣ Criação de Recurso
No menu lateral, clique em "Criar um recurso".
Pesquise por SQL Database (ou outro tipo de banco desejado, como PostgreSQL, MySQL, MariaDB).
Clique em Criar.

### 3️⃣ Definições Básicas
Assinatura (Subscription): escolha a vinculada à sua conta.
Grupo de Recursos (Resource Group): crie um novo ou use um existente.
Nome do Banco de Dados: defina o nome único.
Servidor: se não houver, crie um novo, definindo:
- Nome do servidor
- Login do administrador
- Senha
- Região

### 4️⃣ Configurações de Rede
Configure o firewall para permitir acesso:
Apenas de dentro do Azure.
Ou de IPs públicos específicos (ex.: seu computador).
Habilite Azure Defender se necessário.

### 5️⃣ Revisão e Criação
Clique em Revisar + Criar.
Aguarde a implantação do recurso.

### 6️⃣ Conexão ao Banco
Use Azure Data Studio, SQL Server Management Studio (SSMS) ou outra ferramenta.
Conecte-se ao servidor com:
- Servidor: <nomeservidor>.database.windows.net
- Usuário: login definido
- Senha: senha configurada
- Banco de Dados: o nome criado
