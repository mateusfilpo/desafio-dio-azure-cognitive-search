# Projeto: Análise de Reclamações de Clientes - Rede Nacional de Café

## Objetivo

Este projeto tem como objetivo criar uma ferramenta de pesquisa para coletar, analisar e entender as opiniões dos clientes de uma rede nacional de café. Através do uso do Azure, vamos realizar a análise de dados de reclamações e identificar pontos de melhoria para o serviço.

## Passo a Passo para Configuração

### 1. Criar um Repositório no GitHub

- Crie um repositório no GitHub com o nome de sua preferência.
- Inclua os arquivos de código-fonte, como scripts de configuração e integração com a plataforma Azure.

### 2. Criar Grupo de Recursos no Azure

- Acesse o portal do Azure e crie um novo **Grupo de Recursos**. 
- O grupo de recursos irá agrupar os serviços necessários para o projeto.

### 3. Criar os Serviços do Azure

#### **3.1. Azure AI Search**
- Crie o serviço **Azure AI Search**, que será responsável por realizar as pesquisas e análises dos dados de reclamações.
- Configure os parâmetros de pesquisa para melhor atender às necessidades do projeto.

#### **3.2. Azure AI Services**
- Crie o serviço **Azure AI Services**, que irá enriquecer as pesquisas com capacidades de inteligência artificial, como análise de sentimentos e insights dos dados.

#### **3.3. Conta de Armazenamento no Azure**
- Crie uma **Conta de Armazenamento** no Azure para armazenar os dados que serão analisados.
- Configure a conta de armazenamento para permitir uploads de documentos.

### 4. Configuração de Acesso

#### **4.1. Liberar Acesso ao Container de Blob**
- No Azure Storage, crie um **Container de Blob**.
- Libere o acesso anônimo para que os dados possam ser acessados sem autenticação.

#### **4.2. Upload de Documentos para o Container**
- Realize o upload de documentos de reclamações no container de Blob. Esses documentos serão utilizados para a análise e pesquisa.

### 5. Importação de Dados para o Azure AI Search

- Acesse o serviço **Azure AI Search** e importe os documentos carregados no container de Blob.
- Configure o serviço para buscar nos documentos e analisar as reclamações dos clientes de forma eficiente.

### 6. Análise e Insights

- Após a importação dos dados, utilize os recursos do Azure AI Search e AI Services para analisar as reclamações.
- Aplique técnicas de análise de sentimentos para identificar a percepção dos clientes e melhorar o serviço.

## Ferramentas Beneficiadas por Este Tipo de Pesquisa

- **Azure AI Search**: Facilita a busca e indexação de dados, tornando as pesquisas mais rápidas e precisas.
- **Azure AI Services**: Enriquecem os dados com capacidades de inteligência artificial, como análise de sentimentos, para fornecer insights acionáveis.
- **Azure Blob Storage**: Armazena grandes volumes de dados de forma segura e acessível.

## Aprendizados Adquiridos

- Como integrar múltiplos serviços do Azure para criar uma solução completa de análise de dados.
- Como configurar e utilizar o Azure AI Search para buscar e indexar dados de forma eficaz.
- Como utilizar Azure AI Services para aplicar inteligência artificial a grandes volumes de dados e gerar insights.
- A importância de configurar o acesso e a segurança de dados corretamente, utilizando o armazenamento em Blob e liberando acessos anônimos.

## Links Úteis

- [Documentação do Azure AI Search](https://learn.microsoft.com/en-us/azure/search/)
- [Documentação do Azure AI Services](https://learn.microsoft.com/en-us/azure/cognitive-services/)
- [Documentação do Azure Blob Storage](https://learn.microsoft.com/en-us/azure/storage/blobs/)
