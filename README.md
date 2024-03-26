# 🕵️‍♀️**Explorando os Serviços de AI do Azure para Mineração de Dados em Documentos: Um Laboratório Prático**

**Objetivo:** Este laboratório tem como objetivo explorar as funcionalidades da IA do Azure para extrair insights de documentos e aplicar essas habilidades no dia a dia de uma organização, independentemente do seu porte.

### ⚙️Recursos Utilizados:

- **Azure AI Search:** Permite a criação de um índice de pesquisa de documentos, possibilitando a consulta e a extração de informações.
- **Azure AI Services:** Oferece diversos serviços de IA, como análise de sentimento, reconhecimento de entidades e classificação de texto.
- **Armazenamento do Azure:** Armazena os documentos que serão processados.

### 📚Etapas:

1. **Configurando os Recursos:**
- **Criar um recurso no Azure AI Search:**
  - Acesse o Portal do Azure e procure por "Azure AI Search".
  - Clique em "Criar" e siga as instruções para criar um novo recurso.
  - Escolha um nome, defina a região e o SKU (nível de serviço) desejado.

- **Criar um recurso no Azure AI Services:**
  -  Acesse o Portal do Azure e procure por "Azure AI Services".
  - Clique em "Criar" e siga as instruções para criar um novo recurso.
  - Escolha um nome, defina a região e o SKU desejado.

- **Criar uma conta de armazenamento:**
  - Acesse o Portal do Azure e procure por "Armazenamento do Azure".
  - Clique em "Criar conta de armazenamento".
  - Escolha um nome, defina a região e o tipo de conta desejada.

2. **Carregando os Documentos:**

- Acesse o portal do Armazenamento do Azure.
- Navegue até o contêiner criado.
- Clique em "Carregar" e selecione os arquivos que deseja processar.

3. **Indexando os Documentos:**

- No Portal do Azure, acesse o recurso do Azure AI Search criado.
- Na guia "Visão geral", clique em "Importar dados".
- Selecione o contêiner e os arquivos que deseja indexar.
- Configure as opções de indexação, como o tipo de análise a ser realizada.
- Clique em "Enviar" para iniciar o processo de indexação.
- O indexador é executado automaticamente, abaixo segue imagem de  resultado após o término:

<p>

<div align="center">
 <img src="https://github.com/LohSilva/Lab_CognitiveSearch/blob/main/inputs/result_index.png" width="600" />
</div>

</p>
  
4. **Consultando o Índice:**

- Utilize o Search Explorer (Gerenciador de Pesquisa) para consultar o índice criado.
- O Search Explorer é uma ferramenta integrada ao Portal do Azure que permite realizar consultas e visualizar os resultados.
- Experimente diferentes tipos de consultas para explorar as informações extraídas dos documentos.

Imagens das consultas realizadas durante o laboratório:

*Consulta da quantidade de documentos analisados:*
<p>

<div align="center">
 <img src="https://github.com/LohSilva/Lab_CognitiveSearch/blob/main/inputs/json_count.png" width="600" />
</div>

</p>

*Consulta por localização:*
<p>

<div align="center">
 <img src="https://github.com/LohSilva/Lab_CognitiveSearch/blob/main/inputs/json_localizacao.png" width="600" />
</div>

</p>

*Consulta por sentimentos negativos:*
<p>

<div align="center">
 <img src="https://github.com/LohSilva/Lab_CognitiveSearch/blob/main/inputs/json_sentimento_negativo.png" width="600" />
</div>

</p>
5. **Aplicações possíveis:**

- Utilizar os insights extraídos para tomar decisões mais inteligentes.
- Automatizar tarefas repetitivas, como a classificação de documentos.
- Criar painéis e relatórios para visualizar as informações de forma mais intuitiva.

**Exemplo de aplicação:**

Uma empresa de contabilidade pode utilizar os Serviços de AI do Azure para extrair automaticamente informações de notas fiscais, como data, valor e tipo de despesa. Essas informações podem ser utilizadas para gerar relatórios financeiros, automatizar o processo de lançamento de notas fiscais e identificar possíveis fraudes.

**Benefícios:**

- Aumento da eficiência e da produtividade.
- Melhoria na tomada de decisões.
- Redução de custos.
- Maior competitividade.

### 🚀Conclusão:

A IA do Azure oferece uma ampla gama de ferramentas para extrair insights de documentos e transformar dados em conhecimento. Este laboratório forneceu uma introdução prática à utilização desses serviços. 


