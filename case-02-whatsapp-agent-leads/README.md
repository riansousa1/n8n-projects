# Case 2 - Agente de IA intregrado ao WhatsApp +  registros de leads no Google Sheets

## Descrição
Projeto desenvolvido na plataforma n8n para integrar um agente de IA intregrado ao WhatsApp, com armazenamento automático de leads no Google Sheets.

## Funcionalidades
- Webhook com o Zapi para comunicação via método POST
- Estrutura if para evitar entradas de grupos e outras exceções
- Manipulação e tratamento de dados através do Edit Fields
- Integração com Google Sheets para registro de leads
- Integração com agente de IA (memória de curto prazo, modelo Groq Chat, prompt base humanizado, ferramentas externas como calculadora e Wikipedia)

## Tecnologias utilizadas
- n8n
- Google Sheets
- API externa ZAPI

- ## Fluxo de desenvolvimento

- ![Fluxo de desenvolvimento agente de ia com integração WhatsApp + registros de leads no google sheets](https://github.com/riansousa1/n8n-projects/raw/main/case02img.png?raw=true)
