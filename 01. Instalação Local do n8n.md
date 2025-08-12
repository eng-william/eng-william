## 🚀 Instalação Local do n8n - Windows

O **n8n** (pronuncia-se "*n-eight-n*") é uma ferramenta de automação de **workflows de código aberto**, que permite integrar diferentes serviços, aplicativos e bancos de dados de forma **visual**, com pouca ou nenhuma necessidade de programação.

Ele permite que você crie integrações automáticas entre sistemas, como por exemplo:

- ✉️ Quando um novo e-mail chega no Gmail, salvar o anexo no Google Drive.
- 👥 Quando um novo cliente é adicionado ao CRM, enviar uma mensagem no Slack.
- 🌐 Obter dados de uma API e armazenar os resultados em um banco de dados.

---

## ⚙️ Formas de Execução do n8n

Você pode executar o n8n de três formas:

1. ☁️ **Na nuvem**, através de uma assinatura no site oficial em [n8n.io](https://n8n.io/)
2. 🔐 **Em um servidor privado**, como a Hostinger, DigitalOcean, Linode, Vultr, Hetzner, AWS, Google Cloud ou Azure.
3. 💻 **Localmente**, no seu próprio computador.

> Este guia cobre a **instalação local no Windows**, ideal para estudar e testar seus workflows.

---

## 🧰 Pré-requisitos: Instalando o Node.js

Antes de instalar o n8n, você precisa ter o **Node.js** instalado em sua máquina.

### 🔽 Passos para instalação do Node.js:

1. Acesse: [https://nodejs.org/pt](https://nodejs.org/pt)
2. Clique no botão **"Get Node.js"** e selecione o instalador adequado para **Windows**.
3. Escolha a versão de acordo com a arquitetura do seu sistema (32 ou 64 bits).
4. Baixe e instale o arquivo `.msi`.
5. Após a instalação, abra o **Prompt de Comando** e verifique a instalação digitando `npm -v`

Se o número da versão for exibido, o Node.js e o npm foram instalados corretamente ✅

---

## 📦 Instalando o n8n com npx

Com o Node.js instalado, você pode iniciar o n8n usando o `npx`, que instala e executa pacotes temporariamente.

No **Prompt de Comando**, digite `npx n8n`

🔄 Aguarde o processo de instalação.

Após a instalação, aparecerá uma mensagem solicitando que você pressione a tecla `o`

Isso abrirá o n8n em seu navegador padrão.

🆕 Na primeira execução, será solicitado um cadastro rápido para gerar uma **chave de ativação gratuita**.

---

## 🧪 Comandos Básicos do n8n

| Ação                        | Comando             |
|-----------------------------|---------------------|
| 🟢 Iniciar o n8n            | `npx n8n`           |
| 🔄 Atualizar o n8n          | `npm update -g n8n` |
| 📝 Listar versão instalada  | `npx n8n --version` |

📚 *Agora você está pronto para começar a criar seus próprios fluxos de trabalho com o n8n localmente!*
