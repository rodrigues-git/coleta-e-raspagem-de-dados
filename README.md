# Portfólio de Coleta e Raspagem de Dados

Este repositório contém as atividades realizadas durante a disciplina de Coleta e Raspagem de Dados.

## Atividades

| Unidade | Atividade | Competências principais |
|---|---|---|
| 1 | [Tipos e extração de dados](unidade-1/01-tipos-e-extracao-de-dados/README.md) | Conversão de percentuais e estoques |
| 1 | [Leitura de TXT, CSV e PDF](unidade-1/02-leitura-de-arquivos/README.md) | Leitura de arquivos |
| 1 | [Web scraping de citações](unidade-1/03-web-scraping/README.md) | Requisições HTTP |
| 1 | [Consumo da API Rick and Morty](unidade-1/04-consumo-de-api/README.md) | Consumo de API REST |
| 2 | [Integração de multas ambientais](unidade-2/01-integracao-de-dados/README.md) | Leitura de CSV com ponto e vírgula |
| 2 | [Limpeza de dados de automóveis](unidade-2/02-limpeza-de-dados/README.md) | Programação orientada a objetos |

## Organização

Cada atividade possui um `README.md`, um notebook `analise.ipynb` e, quando necessário, uma pasta `dados/` com os arquivos originais. Os notebooks independem uns dos outros. As duas atividades de coleta online precisam de internet.

## Executar no computador

Com Python 3.12 instalado, abra um terminal nesta pasta:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m jupyterlab
```

Navegue até uma atividade, abra `analise.ipynb` e selecione **Restart Kernel and Run All Cells**. Use o ambiente em que instalou as dependências. A pasta da atividade deve ser o diretório de trabalho do notebook.

## Sobre os dados e a revisão

Os arquivos de entrada foram copiados sem alterações. Os exemplos da atividade de tipos de dados são sintéticos. As origens e as limitações estão descritas nos READMEs de cada atividade. A procedência exata da base Automobile ainda precisa ser documentada. As bases do IBAMA incluem identificadores pessoais no material original; as saídas da análise evitam reproduzi-los.

Este portfólio mantém o caráter de trabalhos de formação, sem apresentar as atividades como projetos de produção.
