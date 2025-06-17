# megacore_devops_pipeline
Simulação de CI usando GitHub Actions

# MegaCore DevOps - Simulação de Pipeline

Este projeto simula uma pipeline de integração contínua usando GitHub Actions.

## Objetivo
Executar um teste automático para validar o total de vendas mensais da MegaCore Labs.

## Teste Automatizado
O arquivo `test_codigo.py` verifica se o total de vendas está entre R$ 5.000 e R$ 10.000.

## Pipeline DevOps
A cada commit no branch `main`, o GitHub Actions executa automaticamente o teste.

## Como Funciona
- Código principal: `codigo.py`
- Teste: `test_codigo.py`
- Pipeline CI: `.github/workflows/python-app.yml`

Pode realizar um commit de teste. Se os valores estiverem fora da faixa, a pipeline falhará.
