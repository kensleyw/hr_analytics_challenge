# HR Analytics Challenge

Este projeto foi realizado como parte do desafio de análise de dados da WNS Analytics Hackathon 2018, disponível em [Analytics Vidhya](https://datahack.analyticsvidhya.com/contest/wns-analytics-hackathon-2018-1/#ProblemStatement). O desafio consiste em prever se um funcionário será promovido após um processo de avaliação.

![Imagem de Capa](https://datahack-prod.s3.ap-south-1.amazonaws.com/__sized__/contest_cover/hr_1920x480_s5WuoZs-thumbnail-1200x1200-70.jpg)

## Descrição do Problema

O cliente é uma grande multinacional com nove setores verticais amplos. Eles enfrentam dificuldades na identificação e preparação de funcionários para promoção, especialmente para cargos de gerência e abaixo. O processo atual é moroso, com atrasos na transição para novas funções. O objetivo é prever se um funcionário será promovido após um ponto de verificação específico.

## Dados

Os dados fornecidos incluem atributos sobre o desempenho passado e atual dos funcionários, juntamente com dados demográficos. Alguns dos atributos fornecidos são:

- `employee_id`: ID único do funcionário
- `department`: Departamento do funcionário
- `region`: Região de emprego
- `education`: Nível de educação
- `gender`: Gênero do funcionário
- `recruitment_channel`: Canal de recrutamento
- E outros atributos relacionados ao desempenho, treinamento, idade, etc.

## Preparação e Análise dos Dados

O script realiza as seguintes etapas:

1. Carregamento dos dados de treinamento e teste.
2. Análise descritiva dos dados.
3. Tratamento de valores ausentes e duplicados.
4. Análise exploratória dos dados, incluindo visualizações.
5. Engenharia de features, como codificação one-hot para variáveis categóricas.
6. Seleção de features relevantes.
7. Treinamento de modelos de machine learning, incluindo XGBoost, ExtraTreesClassifier, RandomForestClassifier, etc.
8. Avaliação dos modelos com métricas como F1 Score e Acurácia.
9. Validação do modelo com dados de validação.
10. Salvamento do arquivo de solução.

## Como Usar

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/nome-do-repositorio.git
```


2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Abra o notebook no Colab, VSCode, Jupyter ou em outra  IDE que já esteja familiarizado:
```bash
HR_Analytics_Challenge.ipynb
```

Isso executará o script e realizará todas as etapas mencionadas acima, incluindo a análise de dados, treinamento de modelos e geração do arquivo de solução.

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar solicitações de recebimento.


