# Projeto em fase inicial de desenvolvimento

## Contexto:
 + Boletos bancários são amplamente usados como meio de cobrança.
 + Contas fraudulentas podem emitir boletos em massa para vítimas que acreditam estar pagando fornecedores legítimos.
 + Nem sempre existe um mecanismo simples para identificar rapidamente emissores suspeitos.

## Problema
+ Identificar precocemente contas potencialmente fraudulentas com base em padrões comportamentais de emissão de boletos ao longo do tempo.

## Hipóteses
 1. Contas fraudulentas apresentam padrões de comportamento diferentes de contas legítimas, como:
    1. maior volume de emissão em pouco tempo
    2. início rápido de atividade após abertura
    3. maior taxa de contestação ("não reconheço")
    4. padrões de emissão menos estáveis

## Objetivo
+ Construir um modelo de classificação capaz de estimar o risco de fraude de contas emissoras a partir de variáveis comportamentais agregadas.

##Abordagem:
+ Criar um dataset sintético simulando contas legítimas e fraudulentas
+ Modelar variáveis comportamentais
+ Treinar modelos de classificação
+ Avaliar capacidade de separar padrões