# Desafio de análise de dados - escolas

Este projeto reúne a análise exploratória de dados de escolas e estudantes, incluindo preparação dos dados, visualizações, comparações estatísticas e um relatório final da solução.

## Estrutura do projeto

- [Desafio.ipynb](Desafio.ipynb): notebook principal com a análise e os gráficos.
- [relatorio.pdf](relatorio.pdf): relatório final do desafio em formato PDF.
- [descricao_desafio_analise_modelagem_dados.pdf](descricao_desafio_analise_modelagem_dados.pdf): descrição do problema e do desafio.
- [base_de_dados](base_de_dados): pasta com os arquivos CSV utilizados na análise.
- [requirements.txt](requirements.txt): dependências do projeto.

## Dados

Os arquivos do dataset estão na pasta [base_de_dados](base_de_dados) e foram configurados para funcionar com caminhos locais, sem depender do ambiente do Google Drive ou do Colab.

Arquivos disponíveis:

- `num_school_data.csv`
- `cat_school_data.csv`
- `num_student_data.csv`
- `cat_student_data.csv`

## Como executar

1. Abra a pasta do projeto no VS Code.
2. Crie um ambiente virtual, se desejar, e instale as dependências:

```bash
python -m pip install -r requirements.txt
```

3. Abra o notebook [Desafio.ipynb](Desafio.ipynb).
4. Execute as células em ordem.

## Observação sobre caminhos

O notebook original utilizava caminhos absolutos do Google Drive/Colab (`/content/drive/...`), o que quebrava a execução em ambientes locais. Os caminhos foram ajustados para usar a base do projeto atual, permitindo que os dados sejam lidos corretamente no computador local.

## Dependências principais

- pandas
- numpy
- matplotlib
- seaborn
- scipy

## Relatório

O trabalho final também está disponível em [relatorio.pdf](relatorio.pdf), contendo a consolidação dos resultados, interpretações e conclusões da análise.
