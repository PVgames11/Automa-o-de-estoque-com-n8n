# Automação de Monitoramento de Estoque com n8n

Automação desenvolvida utilizando n8n para monitorar produtos abaixo do estoque mínimo e enviar automaticamente um relatório por e-mail.

## Objetivo

Automatizar o processo de identificação de produtos com estoque abaixo do mínimo, evitando a necessidade de realizar essa verificação manualmente.

##  Funcionamento

O workflow executa as seguintes etapas:

1. O `Schedule Trigger` inicia a automação em um horário programado.
2. O n8n consulta os produtos armazenados no Google Sheets.
3. O workflow filtra os produtos que estão abaixo do estoque mínimo.
4. Os dados filtrados são convertidos em um arquivo Excel.
5. O relatório é enviado automaticamente por e-mail.

##  Tecnologias

* n8n
* Google Sheets
* Excel
* Gmail
* Automação de processos
* Workflows

##  Fluxo

Schedule Trigger → Google Sheets → Filter → Convert to XLSX → Gmail

## 📷 Workflow

![Workflow da automação](workflow.png)

## 🚀 Aprendizados

Este projeto foi desenvolvido como parte dos meus estudos em automação de processos, com foco em integração de ferramentas, manipulação de dados e criação de workflows automatizados.
