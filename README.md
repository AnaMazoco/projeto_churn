# **Análise Exploratória de Dados Churn**

### Introdução

Esse projeto investigou e validou o aumento recente na taxa de Churn de uma empresa que atua no modelo SaaS (Software as a Service), por meio da análise exploratória dos dados, identificando padrões de comportamento que possam apoiar a equipe de negócios.

O resultado da análise exploratória dos dados produziu uma apresentação de negócios contendo os principais insights obtidos e um notebook comentado em Python incluindo todo o tratamento de dados e a análise realizada.

[Apresentação - Churn](https://github.com/AnaMazoco/projeto_churn/blob/main/Analise%20Churn.pdf)

Saiba mais sobre o projeto abaixo.

### Índice

1. Contexto e premissas para a análise
2. Ferramentas utilizadas
3. Método para solução do projeto
4. Resultado do projeto
5. Conclusão
6. Recomendações


### 1. Contexto e premissas para a análise

Esse projeto tem como princípio uma suspeita levantada sobre o aumento da taxa churn de uma empresa que atua como modelo SaaS. Com base nisso, foi feita a análise exploratória de dados com o objetivo de confirmar a suspeita sobre o aumento da taxa churn e, identificar padrões e comportamentos dos clientes que pudessem estar associado ao cancelamento.

A base de dados utilizada foi obtida da plataforma EBA:[](https://renatabiaggi.com/eba-analista/). Contém 7.043 registros de empresas clientes, com informações sobre o perfil cadastral, tempo de permanência, frequência de usos das funcionalidades do sistema, receita gerada, status churn e entre outros.

O tratamento e a análise dos dados foram realizados em Python.

Os principais insights encontrados pela análise foram organizados em uma apresentação de negócios.


### 2. Ferramentas utilizadas

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`· `Power Point`


### 3. Método para solução do projeto

Esse projeto foi desenvolvido por meio de uma Análise Exploratória de Dados, buscando responder as perguntas norteadoras formuladas e separado pelas seguintes partes:

1. Exploração Univariada:
   Nesta etapa, o objetivo da análise foi explorar os dados e entender os tipos de variáveis, investigar a existência de valores nulos ou faltantes, verificar a qualidade dos dados e analisar a distribuição de variáveis categóricas e numéricas.

2. Exploração multivariável:
   Nesta etapa, o objetivo da análise foi cruzar as variáveis disponíveis com a variável alvo 'churn' e analisar padrões que pudessem estar associados ao churn.

As perguntas norteadoras desse projeto estão dentro do script python dentro desse repositório.


### 4. Resultado do projeto

1. O resultado da análise exploratória dos dados produziu uma apresentação de negócios contendo os principais insights obtidos, e pode ser analisado no seguinte link:
   [Apresentação - Churn](https://github.com/AnaMazoco/projeto_churn/blob/main/Analise%20Churn.pdf)

2.  O notebook comentado em Python incluindo o tratamento de dados e a análise completa, pode ser visualizado no seguinte link:
   [Notebook](https://github.com/AnaMazoco/projeto_churn/blob/main/ChurnAna.ipynb)


### 5. Conclusão

A análise detalhada dos dados de churn revelou padrões importantes para a gestão e retenção de clientes em negócios de assinatura. Os principais achados foram:

- **Aumento recente do churn:** Houve uma elevação significativa na taxa de churn nos meses mais recentes analisados (abril e maio de 2025), indicando um possível problema pontual ou estrutural que merece investigação adicional.
- **Engajamento como fator crítico:** Clientes que nunca utilizaram módulos essenciais do sistema, como o módulo financeiro, apresentam risco de churn muito superior. O engajamento com funcionalidades-chave é um dos maiores discriminadores de retenção.
- **Tipo de contrato influencia retenção:** Contratos de curto prazo (mês-a-mês) têm taxas de churn muito mais altas do que contratos anuais ou trimestrais. Incentivar contratos mais longos pode ser uma estratégia eficaz para aumentar a retenção.
- **Ticket médio e valor acumulado:** Clientes de menor receita mensal e maior receita total acumulada tendem a permanecer mais tempo, reforçando a importância de estratégias para aumentar o lifetime value.
- **Segmentação por porte e perfil:** Variáveis como porte da empresa, número de funcionários e presença de contador têm influência, mas são menos determinantes do que engajamento e tipo de contrato.


### 6. Recomendações

- Investigar causas do aumento recente do churn (mudanças de produto, preço, suporte, concorrência).
- Focar em ações de engajamento para clientes pouco ativos, especialmente nos módulos mais relevantes.
- Incentivar migração para contratos de maior prazo.
- Monitorar de perto clientes de baixo ticket e baixo uso, pois concentram maior risco de cancelamento.
