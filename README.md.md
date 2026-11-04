# Meu Orçamento Familiar

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](./LICENSE)
[![Status: Em Desenvolvimento](https://img.shields.io/badge/Status-Em%20Desenvolvimento-success?style=for-the-badge)]()

*Sistema prático e automatizado para controle, projeção e análise de finanças pessoais e familiares.*

</div>

---

## Sobre o Projeto

O **Meu Orçamento Familiar** é um projeto voltado para a centralização, organização e análise do planejamento financeiro doméstico. A proposta é transformar os lançamentos diários de receitas, despesas e investimentos em visualizações claras e relatórios práticos para auxílio na tomada de decisões.

---

## Funcionalidades Esperadas

- **Gestão de Fluxo de Caixa:** Lançamento e categorização de receitas, despesas fixas e despesas variáveis.
- **Análise Qualitativa e Quantitativa:** Apuração de saldos, percentuais de gastos por categoria e identificação de gargalos.
- **Projeções Orçamentárias:** Planejamento de metas financeiras de curto, médio e longo prazo.
- **Automação de Relatórios:** Scripts de consolidação e limpeza de bases financeiras.

---

## Tecnologias Utilizadas

* **[Python](https://www.python.org/):** Processamento de dados e rotinas de automação.
* **[Pandas](https://pandas.pydata.org/):** Tratamento, agregação e análise das tabelas de lançamentos.
* **Microsoft Excel / CSV:** Modelagem tabular e armazenamento base das transações.

---

## Estrutura do Repositório

```text
Meu-or-amento-familiar/
│
├── data/               # Bases de dados e planilhas de transações (ex: .csv, .xlsx)
├── notebooks/          # Análises exploratórias e protótipos de dados
├── src/                # Scripts Python para processamento e consolidação financeira
├── .gitignore          # Proteção para garantir que dados reais não sejam enviados ao GitHub
├── LICENSE             # Licença MIT do repositório
└── README.md           # Documentação principal do projeto
```

---

## Como Executar

### Pré-requisitos
* Python 3.10 ou superior instalado.

### Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/eduardosimoesgeo/Meu-or-amento-familiar.git
   cd Meu-or-amento-familiar
   ```

2. **Criar e ativar o ambiente virtual:**
   ```bash
   python -m venv venv
   
   # No Windows (PowerShell):
   .\venv\Scripts\activate
   
   # No Linux/macOS:
   source venv/bin/activate
   ```

3. **Instalar as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

---

## Privacidade e Segurança

>  **Aviso de Segurança:** Nunca envie planilhas contendo extratos bancários reais, números de documentos ou dados pessoais para o repositório público. Configure seu arquivo `.gitignore` para ignorar pastas contendo dados privados e utilize apenas dados sintéticos/fictícios para testes públicos.

---

## Licença

Este projeto está sob a licença **MIT**. Consulte o arquivo [LICENSE](./LICENSE) para mais informações.

---

<div align="center">
  Desenvolvido por <a href="https://github.com/eduardosimoesgeo">Eduardo Simões</a>.
</div>
