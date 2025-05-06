## Consulta de Dados

## Contexto
Este laboratório explora ferramentas de indexação, pesquisa e inteligência documental utilizando o Azure AI Search, como parte do Bootcamp Microsoft Azure AI Fundamentals, promovido pela DIO.
A Inteligência Documental destaca-se no uso de inteligência artificial por sua capacidade de extrair informações e interpretar conteúdos de forma eficiente. Técnicas como OCR (Optical Character Recognition), indexação de dados e análise de sentimentos tornam possível processar documentos de maneira automatizada e aprofundada.
Neste experimento, aplico essas estratégias para desenvolver uma solução de mineração de conhecimento, analisando avaliações de consumidores de uma cafeteria fictícia por meio da criação de um Azure AI Search index.
Os procedimentos seguem diretrizes da Microsoft Learn, detalhadas na página Explore an Azure AI Search index (UI).

## Processo

Para a execução do laboratório, são necessários três recursos do Azure:
- Azure AI Search – Gerencia a indexação e pesquisa dos documentos.
- Azure AI Services – Enriquecer os dados por meio de funcionalidades de IA.
- Storage Account – Armazena os documentos no ambiente de blob containers.

1️⃣ Carregar os Documentos
- Acesse o Storage Account no Azure.
- Crie um container e envie os arquivos para armazenamento.
2️⃣ Criar o Índice no Azure AI Search
- No Azure AI Search, vá até "Import Data" e selecione o Storage Account como fonte.
- Defina os campos a serem indexados e selecione as habilidades de enriquecimento de dados.
- Publique o índice para processamento.
3️⃣ Realizar Consultas
- Utilize o portal do Azure para executar queries no índice criado.
- Filtre os resultados por localização, sentimento, palavras-chave, entre outros critérios.
- Os retornos aparecem no formato JSON.
4️⃣ Extração de Insights
- Analise os dados indexados para obter informações valiosas.
- Utilize ferramentas de análise de sentimentos e extração de palavras-chave para interpretação das avaliações.

## Conclusão
Em um mundo onde a informação cresce exponencialmente, apenas armazenar dados não basta; é essencial transformá-los em conhecimento útil. A Inteligência Documental permite organizar e interpretar grandes volumes de informações, viabilizando análises estratégicas.
Para empresas, a capacidade de extrair insights a partir desses dados é um diferencial, tornando essa abordagem indispensável em processos de tomada de decisão.
