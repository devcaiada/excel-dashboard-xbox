# Projeto de Criação de Dashboard Utilizando Excel e Copilot

Este projeto tem como objetivo demonstrar a criação de um dashboard de vendas utilizando o Microsoft Excel e o Copilot, uma ferramenta de IA que auxilia na manipulação e análise de dados. O foco é transformar dados brutos em informações visuais claras e úteis, permitindo uma análise eficaz do desempenho de vendas e a tomada de decisões baseadas em dados.

## Visão Geral do Projeto

O projeto consiste em:

1. **Base de Dados**: Utilizamos uma base de dados de assinaturas de serviços de jogos, contendo informações como ID do assinante, nome, plano, data de início, renovação automática, preço da assinatura, tipo de assinatura, e valores de passes de temporada (EA Play e Minecraft).

2. **Análise de Dados**: Através de análises específicas, respondemos perguntas de negócio como o faturamento total de vendas de planos anuais, separando por auto renovação e não auto renovação, e o total de vendas de assinaturas do EA Play e Minecraft Season Pass.

3. **Dashboard**: Criamos um dashboard visual que apresenta os resultados das análises de forma clara e organizada, facilitando a interpretação dos dados.

![dashboard](https://github.com/devcaiada/excel-dashboard-xbox/blob/main/assets/dashboard.png?raw=true)

## Passo a Passo do Projeto

### 1. Preparação da Base de Dados

A base de dados foi organizada em uma planilha do Excel, contendo as seguintes colunas:

- **Subscriber ID**: Identificador único do assinante.
- **Name**: Nome do assinante.
- **Plan**: Tipo de plano (Core, Standard, Ultimate).
- **Start Date**: Data de início da assinatura.
- **Auto Renewal**: Indica se a assinatura é renovada automaticamente (Sim/Não).
- **Subscription Price**: Preço da assinatura.
- **Subscription Type**: Tipo de assinatura (Mensal, Trimestral, Anual).
- **EA Play Season Pass**: Indica se o assinante possui o passe de temporada do EA Play.
- **EA Play Season Pass Price**: Preço do passe de temporada do EA Play.
- **Minecraft Season Pass**: Indica se o assinante possui o passe de temporada do Minecraft.
- **Minecraft Season Pass Price**: Preço do passe de temporada do Minecraft.
- **Coupon Value**: Valor do cupom aplicado.
- **Total Value**: Valor total da assinatura.

### 2. Análise de Dados

Utilizamos o Excel para realizar análises específicas, respondendo às seguintes perguntas de negócio:

- **Pergunta de Negócio 1**: Qual o faturamento total de vendas de planos anuais (contendo todas as assinaturas agregadas)?
- **Pergunta de Negócio 2**: Qual o faturamento total de vendas de planos anuais, separando por auto renovação e não auto renovação?
- **Pergunta de Negócio 3**: Qual o total de vendas de assinaturas do EA Play?
- **Pergunta de Negócio 4**: Qual o total de vendas de assinaturas do Minecraft Season Pass?

Para responder a essas perguntas, utilizamos funções do Excel como `SOMA`, `FILTRO`, e tabelas dinâmicas. O Copilot foi utilizado para auxiliar na criação de fórmulas e na organização dos dados.

### 3. Criação do Dashboard

O dashboard foi criado para visualizar os resultados das análises de forma clara e organizada. Ele inclui:

- **Gráficos de Barras**: Para visualizar o faturamento total de vendas de planos anuais, separando por auto renovação e não auto renovação.
- **Gráficos de Pizza**: Para mostrar a distribuição das vendas de assinaturas do EA Play e Minecraft Season Pass.
- **Tabelas Dinâmicas**: Para resumir os dados e facilitar a análise.

### 4. Utilização do Copilot

O Copilot foi uma ferramenta essencial neste projeto, oferecendo as seguintes funcionalidades:

- **Automatização de Tarefas**: O Copilot ajudou a automatizar a criação de fórmulas e a organização dos dados, economizando tempo e reduzindo erros.
- **Sugestões de Análise**: O Copilot sugeriu análises específicas que poderiam ser realizadas com os dados disponíveis, como a segmentação por tipo de plano e auto renovação.
- **Criação de Gráficos**: O Copilot auxiliou na criação de gráficos e tabelas dinâmicas, sugerindo os melhores tipos de visualização para cada tipo de dado.

## Conclusão

Este projeto demonstra como o Excel, aliado ao Copilot, pode ser uma ferramenta poderosa para a análise e visualização de dados. Através da transformação de dados brutos em informações visuais claras, foi possível obter insights valiosos sobre o desempenho de vendas, facilitando a tomada de decisões baseadas em dados.

## Como Executar o Projeto

1. **Baixe a Base de Dados**: O arquivo `base.xlsx` contém a base de dados utilizada no projeto.
2. **Abra o Arquivo no Excel**: Utilize o Microsoft Excel para abrir o arquivo e explorar as planilhas.
3. **Utilize o Copilot**: Ative o Copilot no Excel para auxiliar na análise e criação do dashboard.
4. **Crie o Dashboard**: Siga os passos descritos neste README para criar o dashboard de vendas.

## Contribuição <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="25" height="25" />

Este projeto foi desenvolvido como parte de um desafio de análise de dados. Contribuições e sugestões são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests no repositório do GitHub.
