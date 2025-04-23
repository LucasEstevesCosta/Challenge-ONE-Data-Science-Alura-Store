# Análise de Dados das Lojas Alura Store para Decisão Estratégica

Neste desafio de Data Science do projeto ONE (Oracle Next Education) em parceria com a Alura Latan, o **propósito principal desta análise é identificar a loja menos eficiente da rede Alura Store, fornecendo ao Senhor João uma recomendação embasada em dados para auxiliar na sua decisão de qual loja vender para iniciar um novo empreendimento.** Através da análise de dados de vendas, desempenho e avaliações de quatro lojas fictícias, buscamos extrair insights valiosos para essa tomada de decisão estratégica.

## Estrutura do Projeto e Organização dos Arquivos

Este projeto está estruturado da seguinte forma:

* `/data`: Este diretório conterá os arquivos CSV com os dados de cada uma das quatro lojas da Alura Store. Os nomes dos arquivos seguirão o padrão `loja_X.csv`, onde `X` representa o número da loja (1 a 4).
* `AluraStoreBr.ipynb`: Este arquivo na pasta `root` é onde se encontra toda a análise exploratória dos dados, criação dos gráficos e a apresentação da recomendação serão desenvolvidas.
* `README.md`: Este arquivo, que você está lendo agora, fornecerá uma visão geral do projeto.

## Exemplos de Gráficos e Insights Obtidos

Na análise encontrará diversos gráficos para visualizar os dados e extrair insights relevantes. Alguns exemplos incluem:

* **Gráfico de barras comparando o faturamento total de cada loja:** Este gráfico permitirá identificar rapidamente qual loja possui o menor volume de vendas.
* ![image](https://github.com/user-attachments/assets/afafc37c-9bf5-4137-9c42-edc114190474)

* **Gráfico de pizza mostrando a distribuição das categorias de produtos mais vendidas por loja:** Isso ajudará a entender o foco de cada loja e identificar possíveis nichos com baixo desempenho.
* ![image](https://github.com/user-attachments/assets/bb1b655f-094d-4abf-8a34-3d3d770efe8c)


Através dessas visualizações e da análise das métricas, esperamos obter insights como:

* Identificação da loja com o menor faturamento e/ou menor crescimento nas vendas.
* Verificação se a loja com pior desempenho possui avaliações de clientes consistentemente mais baixas.
* Detecção de possíveis problemas relacionados ao frete ou a categorias de produtos específicas em alguma das lojas.

### Estrutura dos tópicos
- Importação dos dados
- Funções
- Análise do faturamento
  -  Diferença de faturamento entre as lojas em porcentagem
-  Vendas por Categoria
  -  Comparativo entre as lojas
  -  Detalhamento de cada loja
  -  Quantidade de vendas por categoria
  -  Valor total de vendas por categoria em Reais
  -  Comparação entre as lojas em categorias específicas
- Média de Avaliação das Lojas
- Produtos Mais e Menos Vendidos
- Frete Médio por Loja
- Volume de vendas por Período
- Relatório

## Instruções para Executar o Notebook

Para executar o notebook e reproduzir a análise, siga os seguintes passos:

1.  **Clone o repositório:** Faça um clone deste repositório para o seu ambiente local.
2.  **Navegue até o diretório `notebooks`:** Utilize o terminal ou prompt de comando para acessar a pasta `notebooks`.
3.  **Execute o notebook Jupyter:** Certifique-se de ter o Jupyter instalado em seu ambiente Python. Execute o comando `jupyter notebook` para abrir o notebook no seu navegador.
4.  **Siga as instruções no notebook:** O notebook conterá o código Python para carregar os dados, realizar a análise, gerar os gráficos e apresentar a recomendação final. Execute as células do notebook sequencialmente para acompanhar o processo.
5.  **Visualize os resultados:** Os gráficos gerados e a análise textual estarão visíveis diretamente no notebook.

Esperando que esta versão mais completa atenda às suas necessidades! 😊 Avise se precisar de mais alguma modificação.
