🚢 Desafio Final 1: Conciliação de Planilhas e Desenhos via IA

Projeto 01 | Power Developers Desenvolvedor: Pedro Couto
🔗 [ACESSE A APLICAÇÃO FUNCIONAL AQUI](https://automacao-suprimentos-ws.ai.studio)

🎯 O Problema
No contexto atual da construção naval e engenharia, a conferência de materiais para a montagem das tubulações exige uma rotina altamente manual e exaustiva. O profissional precisa abrir o desenho técnico do projeto, ler a lista de materiais (BOM) e cruzar visualmente e manualmente com o Jobbook (planilha que relaciona todos os materiais importados já consolidados) para identificar o que está faltando. Esse processo repetitivo está sujeito a falhas humanas e consome um tempo valioso da equipe técnica.

💡 A Solução Desenvolvida
Para transformar essa atividade analítica em uma operação eficiente, foi desenvolvido um Dashboard Web interativo alimentado por Inteligência Artificial (Google Gemini).
A aplicação atua como uma "Torre de Controle" que automatiza a leitura do desenho técnico e consolida, em tempo real, essas informações com a fonte de dados estática (Jobbook). O resultado é uma visualização imediata do status do estoque e das necessidades de compra, sem a necessidade de intervenção manual em planilhas.

✨ Principais Funcionalidades
Upload Simplificado (Drag and Drop): Interface fluida onde o usuário apenas arrasta e solta o Desenho Técnico (PDF ou Imagem) para iniciar o processo.
Visão Computacional Avançada: Utilização de IA multimodal para leitura automatizada e extração precisa da lista de materiais (BOM) contida no carimbo do desenho.
Cruzamento de Dados em Tempo Real: O motor lógico compara instantaneamente os itens extraídos do desenho com o estoque disponível no banco de dados do Jobbook.
Sistema de Alertas e Regras de Negócio: Painel visual que categoriza o status de cada peça, indicando quais materiais possuem estoque suficiente e quais precisam ser comprados, já sugerindo a origem (Nacional para quantidades até 10, ou Importado para quantidades maiores).

🛠️ Tecnologias Utilizadas
Google Gemini API: Motor de inteligência artificial e extração de dados visuais.
JavaScript / HTML / CSS: Construção da interface do usuário (Frontend) e lógica de requisições.
Google Sheets: Atuando como banco de dados estático para o Jobbook.

🚀 Guia de Uso (Como Testar)
A aplicação foi construída para ser "Plug and Play", sem necessidade de configurações ou instalações por parte do usuário.
Acesse o link disponibilizado no topo deste README.
Na seção "Entrada do Desenho Técnico", arraste o arquivo de teste (PDF) fornecido pelo desafio para a área pontilhada.
Clique no botão de Analisar Desenho (ou aguarde o processamento automático).
O painel inferior será atualizado instantaneamente com o relatório consolidado, exibindo a "Lista de Compras (Itens Faltantes)" e o "Estoque OK".

