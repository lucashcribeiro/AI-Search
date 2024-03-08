# Configuração da Pesquisa de Satisfação do Cliente - CaféLabAI

Este arquivo **README.md** fornece um guia passo a passo para configurar uma pesquisa de satisfação do cliente utilizando o Azure AI Search. Este projeto visa analisar as reclamações dos clientes de uma multinacional de café, buscando insights para melhorar a qualidade dos serviços em todas as unidades.

## Pré-requisitos

Antes de começar, certifique-se de ter acesso ao [Azure Portal](https://portal.azure.com/) e os seguintes recursos configurados:

1. **Azure AI Search**: Crie um novo serviço Azure AI Search para implementar a pesquisa.

2. **Storage Account**: Crie um novo Storage Account no Azure para armazenar os dados necessários.

## Configuração do Azure AI Search

### Passo 1: Criar Azure AI Search

No [Azure Portal](https://portal.azure.com/), crie um novo serviço Azure AI Search com as configurações desejadas.

### Passo 2: Configurar Storage Account

1. Crie um novo Storage Account no Azure para armazenamento.
2. Dentro do Storage Account, crie um Container chamado "coffelabai" para armazenar os dados da pesquisa.

### Passo 3: Carregar Arquivos

1. Baixe os arquivos necessários do [link fornecido](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html).
2. Descompacte os arquivos.
3. Faça o upload dos arquivos para o Container "coffelabai" no Storage Account.

### Passo 4: Importar Dados no Azure AI Search

1. No Azure AI Search, selecione o serviço criado.
2. Vá para a seção "Importar Dados" e indique a localização dos documentos no Storage Account.
3. Execute a importação para indexar os dados.

## Utilizando a Pesquisa

Após a conclusão da configuração, você terá um mecanismo de busca pronto para análise. Utilize as funcionalidades do Azure AI Search para:

- Realizar pesquisas avançadas.
- Analisar insights e padrões nos dados.
- Identificar tendências nas reclamações dos clientes.

## Possibilidades de Ferramentas Adicionais

Além do Azure AI Search, explore outras ferramentas que podem se beneficiar deste projeto:

- **Power BI**: Crie dashboards interativos para visualizar dados.
- **Azure Machine Learning**: Implemente modelos preditivos para prever problemas futuros.
- **Azure Cognitive Services**: Integre análise de sentimentos para avaliar a satisfação do cliente.

## Aprendizados Adquiridos

Durante o processo de configuração e análise, registre aprendizados valiosos:

- Descubra padrões nos dados de satisfação do cliente.
- Entenda como a pesquisa pode impactar positivamente a qualidade dos serviços.
- Avalie a eficácia das ferramentas escolhidas e ajuste conforme necessário.

**Finalizado!** Configurado com sucesso uma pesquisa de satisfação do cliente com o Azure AI Search. Utilize os insights obtidos para melhorar continuamente a experiência do cliente em todas as unidades da multinacional de café.