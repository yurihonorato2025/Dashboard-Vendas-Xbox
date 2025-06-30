# Dashboard-Vendas-Xbox
Dashboard Vendas Xbox


Dashboard de Vendas no Excel
Visão Geral do Projeto
Este projeto tem como objetivo principal a criação de um dashboard de vendas interativo no Microsoft Excel. A meta é transformar dados brutos de assinaturas em informações visuais claras e úteis, permitindo uma análise eficaz do desempenho de vendas e a tomada de decisões estratégicas baseadas em dados.
O dashboard foi projetado para oferecer uma visão rápida e organizada sobre o total de assinaturas para diferentes produtos, como EA Play Season Pass, Minecraft Season Pass e Xbox Game Pass, além de permitir a filtragem por tipo de assinatura.
Dados Utilizados
O dashboard utiliza um conjunto de dados hipotéticos de assinaturas, contendo as seguintes informações principais:
•	Subscriber ID: Identificador único do assinante.
•	Name: Nome do assinante.
•	Plan: Plano de assinatura.
•	Start Date: Data de início da assinatura.
•	Auto Renewal: Indica se a assinatura possui renovação automática.
•	Subscription Price: Preço base da assinatura.
•	Subscription Type: Tipo geral de assinatura (usado como filtro principal no dashboard).
•	EA Play Season Pass: Indica se o assinante possui o EA Play Season Pass.
•	EA Play Season Pass Price: Preço do EA Play Season Pass.
•	Minecraft Season Pass: Indica se o assinante possui o Minecraft Season Pass.
•	Minecraft Season Pass Price: Preço do Minecraft Season Pass.
•	Coupon Value: Valor de cupons aplicados.
•	Total Value: Valor total da assinatura, considerando preço e cupons.
Esses dados são a base para as Tabelas Dinâmicas e os cálculos que alimentam os indicadores visuais do dashboard.
Dashboard Contém:
•	Filtro: Uma Segmentação de Dados (Slicer) para Subscription Type, permitindo filtrar todos os dados do dashboard.
•	Total Subscriptions EA SEASON: Contagem total de assinaturas que incluem o EA Play Season Pass.
•	Total Subscriptions Minecraft SEASON PASS: Contagem total de assinaturas que incluem o Minecraft Season Pass.
•	Total Subscriptions XBOX GAME PASS: Contagem total de assinaturas do tipo Xbox Game Pass (assumindo que seja um tipo de plano ou assinatura específico).
Tecnologias
•	Microsoft Excel (.xlsx)
Instruções para Reprodução
Para visualizar e interagir com o dashboard, siga os passos abaixo:
1.	Baixe o arquivo Excel: Faça o download do arquivo [NomeDoSeuArquivo].xlsx (ou o nome que você deu ao seu arquivo do dashboard) disponível neste repositório.
2.	Abra o arquivo no Excel: Utilize o Microsoft Excel (versão 2010 ou superior é recomendada para total funcionalidade das Tabelas Dinâmicas e Segmentações de Dados).
3.	Navegue até a planilha "Dashboard": Esta é a planilha principal onde todas as informações e gráficos são exibidos.
4.	Explore os dados:
o	Filtro "Subscription Type": Utilize a segmentação de dados localizada na parte superior do dashboard para filtrar os dados por diferentes tipos de assinatura. Ao clicar em uma opção, todos os totais e gráficos serão atualizados dinamicamente.
o	Totais de Assinaturas: Observe os cartões que exibem a contagem total de assinaturas para EA Play Season Pass, Minecraft Season Pass e Xbox Game Pass.
o	Gráficos (se aplicável): Interaja com quaisquer gráficos adicionais que foram implementados para visualizar tendências ou distribuições.
Estrutura Interna (para referência):
O arquivo Excel contém as seguintes planilhas ocultas que alimentam o dashboard:
•	[Nome da Planilha de Dados Originais]: Contém os dados brutos.
•	Dados EA Play: Tabela Dinâmica utilizada para calcular o total de assinaturas EA Play Season Pass.
•	Dados Minecraft: Tabela Dinâmica utilizada para calcular o total de assinaturas Minecraft Season Pass.
•	Dados Xbox: Tabela Dinâmica utilizada para calcular o total de assinaturas Xbox Game Pass.
•	Outras planilhas de dados dinâmicos: Se foram criadas tabelas dinâmicas adicionais para gráficos.
Para reexibir essas planilhas (caso queira inspecionar as Tabelas Dinâmicas), clique com o botão direito em qualquer nome de planilha visível e selecione "Reexibir...".

