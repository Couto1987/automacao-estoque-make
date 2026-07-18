# 📦 Engenheiro de Suprimentos IA - Dashboard de Estoque

## 🎯 O Problema
No gerenciamento de obras e projetos de engenharia, a conferência de materiais entre o projeto técnico (Jobbook) e o estoque real é um processo manual, lento e suscetível a falhas. Identificar o que precisa ser comprado, se o item é nacional ou importado, e calcular a quantidade exata faltante demanda horas de análise humana.

## 💡 A Solução
Desenvolvi uma aplicação web integrada com Inteligência Artificial para automatizar essa conferência. O usuário faz o upload de um documento em PDF, e o sistema processa os dados cruzando-os com uma base de estoque simulada. O resultado é devolvido em tempo real em uma interface visual (Dark Mode) clara e objetiva.

## 🚀 Principais Funcionalidades
* **Upload Dinâmico:** Interface intuitiva para recebimento de arquivos PDF.
* **Processamento via IA (Gemini):** O backend lê e interpreta as demandas do arquivo através da API do Google Gemini.
* **Classificação Automática:** Identificação inteligente de itens (Nacional vs. Importado) com base em códigos de transporte.
* **Cálculo de Déficit:** Matemática automatizada da quantidade faltante (Demanda - Enviado).
* **Interface Responsiva:** Dashboard moderna que separa visualmente os itens que precisam de compra (alertas vermelhos) dos itens com estoque OK (alertas verdes).

## 🛠️ Tecnologias Utilizadas
* **Front-end:** JavaScript / React (Via Lovable)
* **Back-end & Automação:** Make.com (Webhooks)
* **Inteligência Artificial:** Google Gemini AI API

## 🔗 Link da Aplicação
Você pode testar a aplicação funcional diretamente aqui: https://hook-sync-dash.lovable.app/

