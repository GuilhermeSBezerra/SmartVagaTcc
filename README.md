# 🚗 SmartVaga — Sistema Inteligente de Estacionamento

Sistema web desenvolvido para gerenciamento inteligente de estacionamentos, utilizando Node.js, MySQL e geração de relatórios em PDF.

---

# 📥 Download do Projeto

Clone o repositório ou faça o download do ZIP:

```bash
git clone https://github.com/GuilhermeSBezerra/SmartVaga.git
```

ou

- Clique em **Code**
- Depois em **Download ZIP**

---

# ⚙️ Pré-requisitos

Antes de executar o sistema, é necessário instalar:

- Node.js
- XAMPP
- Visual Studio Code
- Java JDK

---

# 🟢 1. Instalação do Node.js

Baixe:

👉 https://nodejs.org

Após instalar, verifique no terminal:

```bash
node -v
npm -v
```

---

# ☕ 2. Instalação do Java

Baixe:

👉 https://www.oracle.com/java/technologies/downloads/

Verifique a instalação:

```bash
java -version
```

---

# 🗄️ 3. Instalação do XAMPP

Baixe:

👉 https://www.apachefriends.org/pt_br/index.html

Após instalar:

- Abra o **XAMPP Control Panel**
- Inicie:
  - Apache
  - MySQL

---

🛢️ 4. Criando o Banco de Dados

Com o MySQL iniciado:

1. Acesse:

http://localhost/phpmyadmin

2. Clique em **Novo** e crie um banco chamado:

meubanco

### 📥 4.1 Importando a Estrutura do Banco

Após criar o banco:

1. Clique no banco **meubanco**.
2. Acesse a aba **Importar**.
3. Clique em **Escolher arquivo**.
4. Selecione o arquivo SQL disponibilizado no repositório do projeto.
5. Clique em **Executar**.

O arquivo SQL criará automaticamente todas as tabelas e estruturas necessárias para o funcionamento do sistema SmartVaga.

Após a importação, verifique se as tabelas foram criadas corretamente dentro do banco **meubanco**.

⚠️ Importante:

Sem importar o arquivo SQL, o sistema apresentará erros como:

* Unknown database 'meubanco'
* Table doesn't exist
* ER_NO_SUCH_TABLE

Portanto, a importação do banco de dados é obrigatória antes de iniciar o servidor.

---

# 💻 5. Abrindo o Projeto no VS Code

Abra o Visual Studio Code.

Depois:

```text
Arquivo → Abrir Pasta
```

Selecione a pasta do projeto SmartVaga.

---

# 📦 6. Instalando as Dependências

Abra o terminal do VS Code e execute:

```bash
npm install
```

Esse comando instalará todas as dependências necessárias.

---

# 🚀 7. Executando o Servidor

No terminal execute:

```bash
node server.js
```

Se estiver tudo correto aparecerá:

```text
🚗 Servidor rodando com sucesso em http://localhost:3000
```

---

# 🌐 8. Abrindo o Sistema

Abra o navegador e acesse:

```text
http://localhost:3000
```

---

# ⚠️ Possíveis Erros

## ❌ Unknown database 'meubanco'

Verifique se o banco foi criado corretamente no phpMyAdmin.

---

## ❌ MySQL shutdown unexpectedly

- Reinicie o XAMPP
- Execute como administrador
- Verifique conflitos na porta 3306

---

## ❌ Port 443 in use

Existe outro serviço utilizando a porta HTTPS.

---

# 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- TailwindCSS
- JavaScript
- Node.js
- Express
- MySQL
- PDFKit

---

# 👨‍💻 Autor

Desenvolvido por **Guilherme Severino Bezerra**

Projeto acadêmico — SmartVaga 🚗
