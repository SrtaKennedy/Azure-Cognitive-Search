## Azure-Cognitive-Search

Este projeto demonstra como utilizar o Azure Cognitive Search para indexar e consultar dados de forma eficiente. O processo envolve três passos principais: ingestão de dados, criação do índice e execução de consultas.

## Passo a passo

#### 1. Ingestão de Dados

Para ingerir os dados, utilize o script `ingest_data.py` localizado na pasta `scripts/`. Este script lê os dados de um arquivo JSON e os envia para o Azure Cognitive Search.

```bash
python scripts/ingest_data.py --data-file data/sample_data.json
`````

#### 2. Criação do Índice

Após a ingestão dos dados, crie o índice utilizando o script `create_index.py`. Este script configura o índice no Azure Cognitive Search com base nas especificações definidas.

```bash
python scripts/create_index.py --index-name my_index
````

#### 3. Execução de Consultas

Com o índice criado, você pode executar consultas utilizando o script `search_data.py`. Este script permite buscar informações no índice criado.

````bash
python scripts/search_data.py --index-name my_index --query "search term"
````

## Insights e Aprendizados

Durante o desenvolvimento deste projeto, aprendi a importância de uma boa organização dos dados e como o Azure Cognitive Search pode ser uma ferramenta poderosa para realizar buscas eficientes em grandes volumes de dados. Além disso, explorei as possibilidades de integração com outras ferramentas de IA para enriquecer ainda mais as funcionalidades de busca. Também enfrentei alguns desafios como a configuração do ambiente, a ingestão de alguns dados entre outros.


## Possíveis integrações  

**Power BI:** Visualização de dados indexados. <br>
**Azure Machine Learning:** Enriquecimento de dados com modelos de machine learning. <br>
**Azure Functions:** Automação de processos de ingestão e indexação.


