> 🔄 Projeto revisitado e atualizado em 2026 como parte da retomada de estudos em Python e boas práticas de desenvolvimento.
# Email Automatizado em Python

Este projeto é uma retomada de estudos em Python, onde refiz um script de envio de emails automatizados que eu havia desenvolvido no passado.
A ideia foi atualizar bibliotecas, revisar boas práticas e tornar o projeto reproduzível em ambientes diferentes.

## 🎯 Objetivo
- Retomar fluidez com Python e suas bibliotecas
- Aprender o uso de ambientes virtuais (`venv`)
- Praticar versionamento com Git
- Garantir que o código funcione tanto no Google Colab quanto localmente

## ⚙️ O que o projeto faz
- Capta dados de Dólar e do Ibovespa pelo Yahoo Finance
- Manipula os dados para obter informações como fechamento do dia anterior, retorno do mês, e retorno do ano.
- Cria gráficos e tabelas com outros timeframes
- Envia emails automaticamente via SMTP, com os dados captados
- Usa variáveis de ambiente para credenciais
- Pode ser executado via Jupyter Notebook

## 🧰 Tecnologias utilizadas
- Python 3
- Jupyter Notebook
- datetime
- pandas
- yfinance
- matplotlib
- mplcyberpunk
- smtplib
- EmailMessage
- os
- python-dotenv
- Git

## ▶️ Como executar localmente

```bash
python -m venv .venv
source .venv/bin/activate # Linux
pip install -r requirements.txt
jupyter notebook