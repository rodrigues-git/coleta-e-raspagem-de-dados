# Integração de multas ambientais

## Objetivo

Comparar a arrecadação de multas ambientais de RN e PB por tipo de infração, integrando duas bases do IBAMA.

## Habilidades demonstradas

Leitura de CSV com ponto e vírgula; conversão de moeda brasileira; groupby; soma; outer merge e análise de valores ausentes.

## Arquivos e dados

- [Notebook com a análise](analise.ipynb)

- `dados/arrecadacao_de_multas_ambientais_por_bens_tutelados_RN.csv`
- `dados/arrecadacao_de_multas_ambientais_por_bens_tutelados_PB.csv`

Origem indicada no enunciado: portal de dados abertos do IBAMA. Foram preservados os CSVs originais de RN e PB, sem alterações. Os arquivos contêm identificadores pessoais; as prévias do notebook exibem apenas UF, tipo de infração e valor pago.

## Como executar

Instale as dependências seguindo o [README principal](../../README.md). Abra `analise.ipynb` no Jupyter e execute todas as células em ordem, com a pasta desta atividade como diretório de trabalho. Os caminhos de dados são relativos à atividade e dispensam Google Drive.

## Resultado verificado

Integração: 53476 registros RN; 64979 registros PB; 10 categorias; somas preservadas.

## Escopo

Trabalho de portfólio desenvolvido a partir de uma atividade da disciplina de Coleta e Raspagem de Dados. A revisão preserva os objetivos e as soluções centrais, com ajustes de correção e execução local.
