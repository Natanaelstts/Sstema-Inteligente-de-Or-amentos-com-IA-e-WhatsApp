# 🤖 Sistema de Orçamentos Inteligente com IA

Este projeto consiste em um ecossistema de automação de vendas que transforma leads de um formulário em orçamentos personalizados gerados por Inteligência Artificial e enviados automaticamente via WhatsApp.

---

### 🛠️ Tecnologias Utilizadas

![WordPress](https://img.shields.io/badge/WordPress-%2321759B.svg?style=for-the-badge&logo=WordPress&logoColor=white)
![Elementor](https://img.shields.io/badge/Elementor-%2392003B.svg?style=for-the-badge&logo=Elementor&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-FF6C37?style=for-the-badge&logo=n8n&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_IA-F55036?style=for-the-badge&logo=openai&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)

---

### 🚀 O Fluxo do Projeto

1. **Frontend:** Formulário desenvolvido em WordPress/Elementor para captura de leads.
2. **Integração:** O envio do formulário dispara um **Webhook** para o n8n.
3. **Cérebro (IA):** O n8n envia os dados para a **IA (Groq)**, que analisa o pedido com base no estoque.
4. **Dados:** Consulta e registro automático em planilhas do **Google Sheets**.
5. **Automação de Saída:** O orçamento final é enviado de forma humanizada para o **WhatsApp** e **Email** do cliente.

---

### 📂 Como visualizar este projeto

Como o projeto utiliza um ambiente local (LocalWP), deixei disponível neste repositório:
- O arquivo `.json` do fluxo do **n8n** para importação.
- Screenshots do painel administrativo e do fluxo em funcionamento.

---


> Projeto desenvolvido para demonstrar habilidades em **Low-code**, **Automação de Processos** e **Integração de Inteligência Artificial**.
<img width="1629" height="673" alt="image" src="https://github.com/user-attachments/assets/64797ec9-106b-4273-b0cb-603d0b6dad74" />
<img width="1894" height="834" alt="image" src="https://github.com/user-attachments/assets/99544e27-029c-4770-967d-eb6bf9d8f3f3" />

