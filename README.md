<img width="1920" height="1080" alt="Captura de tela de 2026-07-14 22-35-04" src="https://github.com/user-attachments/assets/ce3136de-05e1-4924-9c78-ef4eb4550e41" />
# automacao-estoque-make# Sistema Automatizado de Controle de Estoque e Compras

## 🎯 O Problema
No cenário atual do estaleiro, o cruzamento de dados entre os projetos de engenharia (Jobbook) e o estoque físico é um processo manual, lento e sujeito a falhas humanas. A identificação de peças faltantes e a decisão de importação demandam muito tempo operacional.

## 💡 A Solução Desenvolvida
Foi desenvolvida uma automação em nuvem que integra Inteligência Artificial com planilhas de banco de dados. O sistema funciona como uma esteira invisível: assim que uma nova peça é demandada, o sistema automaticamente busca seu código no inventário geral, calcula as quantidades exatas que faltam para a produção e classifica a origem do item de forma lógica.

## ⚙️ Principais Funcionalidades
* **Busca Dinâmica (Search Rows):** Varredura automática do código da peça em todo o banco de dados do estoque.
* **Cálculo Automático de Faltas:** Processamento matemático em tempo real que subtrai a quantidade já enviada da quantidade demandada no projeto.
* **Decisão Lógica de Origem:** Aplicação de regras condicionais para classificar instantaneamente se o material deve ser tratado como "Nacional" ou "Importado" com base no volume da demanda.

## 🚀 Como Testar a Aplicação
A aplicação está 100% hospedada na nuvem e pronta para uso. Nenhuma instalação é necessária.

1. Acesse o ambiente de entrada de dados através deste link: **https://docs.google.com/spreadsheets/d/1_m8BuM3z0mCclGiEWUepfzlT4MCggxWqujrTgG4EvlQ/edit?usp=sharing**
2. Na aba "Ped. p/ Fazer", simule a entrada de um novo material preenchendo as colunas iniciais (como o Código da peça).
3. Aguarde alguns segundos. O sistema rodará a automação em segundo plano e preencherá automaticamente as colunas "Falta no Estoque" e "Origem".
