---
title: Aspose.Pdf.AI
second_title: Aspose.PDF for .NET API Reference
description: O namespace Aspose.Pdf.AI fornece classes para funcionalidades de IA, incluindo clientes de API e assistentes inteligentes
type: docs
weight: 40
url: /pt/net/aspose.pdf.ai/
---
O **namespace Aspose.Pdf.AI** fornece classes para funcionalidades de IA, incluindo clientes de API e assistentes inteligentes.

## Classes

| Classe | Descrição |
| --- | --- |
| [AIClientBase](./aiclientbase/) | Representa o cliente para acessar a API de IA. |
| [AIClientException](./aiclientexception/) | Representa uma exceção específica para as operações do Cliente de IA. |
| [AICopilotException](./aicopilotexception/) | Representa uma exceção específica para as operações de Copilotos. |
| [AICopilotFactory](./aicopilotfactory/) | Classe de fábrica para criar diferentes tipos de copilotos. |
| [Annotation](./annotation/) | Representa o conteúdo de texto que faz parte de uma mensagem. |
| [AssistantCreateRequest](./assistantcreaterequest/) | Objeto de solicitação para criar um assistente. |
| [AssistantListQueryParameters](./assistantlistqueryparameters/) | Representa o objeto de parâmetros de consulta para listar assistentes. |
| [AssistantListResponse](./assistantlistresponse/) | Representa a resposta contendo uma lista de respostas de assistentes. |
| [AssistantModifyRequest](./assistantmodifyrequest/) | Objeto de solicitação para modificar um assistente. |
| [AssistantResponse](./assistantresponse/) | Representa um assistente que pode chamar o modelo e usar ferramentas. |
| [Attachment](./attachment/) | Representa uma lista de arquivos anexados à mensagem e as ferramentas às quais devem ser adicionados. |
| [BaseListQueryParameters](./baselistqueryparameters/) | Parâmetros de consulta base para listar objetos. |
| [BaseResponse](./baseresponse/) | Classe base para respostas da API. |
| [CancellationTokenExtensions](./cancellationtokenextensions/) | Fornece métodos de extensão para CancellationToken. |
| [ChatMessage](./chatmessage/) | Uma mensagem de conclusão de chat gerada pelo modelo. |
| [Choice](./choice/) | Representa uma escolha em uma resposta de conclusão de chat. |
| [CodeInterpreter](./codeinterpreter/) | Representa os recursos da ferramenta de interpretador de código. |
| [CompletionCreateRequest](./completioncreaterequest/) | Representa uma solicitação para o endpoint Criar Conclusão de Chat. |
| [CompletionFunction](./completionfunction/) | Representa o objeto de função. |
| [CompletionResponse](./completionresponse/) | Representa uma resposta de conclusão de chat retornada pelo modelo, com base na entrada fornecida. |
| [CreateChatCompletionChunkResponse](./createchatcompletionchunkresponse/) | Representa um pedaço transmitido de uma resposta de conclusão de chat retornada pelo modelo, com base na entrada fornecida. |
| [CreateEmbeddingRequest](./createembeddingrequest/) | Representa uma solicitação para o endpoint Criar Embeddings. |
| [CreateEmbeddingResponse](./createembeddingresponse/) | Representa uma resposta do endpoint Criar Embeddings. |
| [CreateFineTuningJobRequest](./createfinetuningjobrequest/) | Representa uma solicitação para o endpoint Criar Trabalho de Ajuste Fino. |
| [CreateFineTuningJobResponse](./createfinetuningjobresponse/) | Representa uma resposta do endpoint Criar Trabalho de Ajuste Fino. |
| [DataResponse&lt;T&gt;](./dataresponse-1/) | Representa uma resposta de dados contendo os dados especificados. |
| [DeleteStatusResponse](./deletestatusresponse/) | Representa o status de uma exclusão de objeto. |
| [DocumentCollection](./documentcollection/) | Representa uma coleção de documentos a serem processados. |
| [Embedding](./embedding/) | Representa um vetor de embedding retornado pelo endpoint de embedding. |
| [Error](./error/) | Representa um erro na resposta da API. |
| [ExpiresAfter](./expiresafter/) | Representa a política de expiração para um armazenamento de vetores. |
| [FileCitation](./filecitation/) | Representa a citação do arquivo. |
| [FileContentResponse&lt;T&gt;](./filecontentresponse-1/) |  |
| [FileCounts](./filecounts/) |  |
| [FileListResponse](./filelistresponse/) | Representa uma resposta de lista de arquivos contendo uma lista de respostas de arquivos. |
| [FileResponse](./fileresponse/) | O objeto FileResponse representa um documento que foi enviado para o OpenAI. |
| [FileSearch](./filesearch/) | Representa os recursos da ferramenta de busca de arquivos. |
| [Function](./function/) | Representa uma função que pode ser chamada pelo modelo. |
| [Hyperparameters](./hyperparameters/) | Representa os hiperparâmetros usados para um trabalho de ajuste fino. |
| [ImageDescription](./imagedescription/) | Representa uma descrição de imagem. |
| [ImageDescriptionResult](./imagedescriptionresult/) | Representa a resposta contendo descrições de imagens. |
| [ImageFile](./imagefile/) | Representa um arquivo de imagem no conteúdo de uma mensagem. |
| [ImageUrl](./imageurl/) | Representa uma URL de imagem no conteúdo de uma mensagem. |
| [IncompleteDetails](./incompletedetails/) | Detalhes sobre o motivo pelo qual a execução está incompleta. Será nulo se a execução não estiver incompleta. |
| [LastError](./lasterror/) | O último erro associado a esta execução. Será nulo se não houver erros. |
| [ListDataResponse&lt;T&gt;](./listdataresponse-1/) | Representa uma resposta de dados de lista contendo informações adicionais, como os primeiros e últimos IDs e se há mais itens. |
| [LlamaChatCompletionRequest](./llamachatcompletionrequest/) | Representa o corpo da solicitação para as solicitações da API ChatGPT. |
| [LlamaChatCompletionResponse](./llamachatcompletionresponse/) | Representa uma resposta de conclusão de chat retornada pelo modelo, com base na entrada fornecida. |
| [LlamaClient](./llamaclient/) | Representa um cliente para interagir com a API Llama. |
| [LlamaCopilotOptionsBase](./llamacopilotoptionsbase/) | Representa as opções base para configurar o LlamaCopilot. |
| [LlamaModels](./llamamodels/) | Contém constantes relacionadas a diferentes modelos Llama. |
| [LlamaSummaryCopilot](./llamasummarycopilot/) | Fornece funcionalidade para obter resumos de documentos usando modelos de IA. Exemplo de uso de criação de um cliente Llama, configuração de opções e uso do copiloto de resumo. Nota: Este copiloto usa a API de conclusão, portanto, a quantidade total de texto que pode ser enviada é limitada pela janela de contexto do modelo. |
| [LlamaSummaryCopilotOptions](./llamasummarycopilotoptions/) | Representa as opções para configurar o OpenAICopilot. |
| [Logprobs](./logprobs/) | Representa informações de probabilidade logarítmica para uma escolha. |
| [MessageContentBase](./messagecontentbase/) | O conteúdo da mensagem em um array de texto e/ou imagens. |
| [MessageContentRequest](./messagecontentrequest/) | O conteúdo da mensagem em um array de texto e/ou imagens. |
| [MessageContentResponse](./messagecontentresponse/) | O conteúdo da mensagem de resposta em um array de texto e/ou imagens. |
| [MessageCreation](./messagecreation/) | Representa a criação de uma mensagem com seu identificador único. |
| [OpenAIAssistantCopilotOptionsBase](./openaiassistantcopilotoptionsbase/) | Representa as opções base para configurar os OpenAICopilots com base na API de Assistentes. |
| [OpenAIChatCopilot](./openaichatcopilot/) | Representa um copiloto de chat para interagir com documentos via modelos de IA. Exemplo de uso de criação de um cliente OpenAI, configuração de opções e uso do ChatCopilot para interagir com consultas de usuários e gerenciar o contexto da conversa. |
| [OpenAIChatCopilotOptions](./openaichatcopilotoptions/) | Representa as opções para configurar o OpenAICopilot. |
| [OpenAIClient](./openaiclient/) | Fornece métodos para interagir com a API OpenAI para gerenciar lotes de arquivos de armazenamento de vetores. |
| [OpenAIContext](./openaicontext/) | Representa os IDs de entidade relacionados a um assistente. |
| [OpenAICopilotOptionsBase](./openaicopilotoptionsbase/) | Representa as opções base para configurar o OpenAICopilot. |
| [OpenAIImageDescriptionCopilot](./openaiimagedescriptioncopilot/) | Fornece funcionalidade de processamento de imagem para a classe OpenAICopilot. Exemplo de uso de criação de um cliente OpenAI, configuração das opções do ImageDescriptionCopilot e uso do copiloto para gerar descrições de imagens e adicionar descrições a documentos anexados. |
| [OpenAIImageDescriptionCopilotExtensions](./openaiimagedescriptioncopilotextensions/) | Fornece métodos de extensão para a classe OpenAIImageDescriptionCopilot. |
| [OpenAIImageDescriptionCopilotOptions](./openaiimagedescriptioncopilotoptions/) | Representa as opções para configurar o OpenAICopilot. |
| [OpenAIModels](./openaimodels/) | Contém os identificadores de modelos OpenAI disponíveis. |
| [OpenAISummaryCopilot](./openaisummarycopilot/) | Fornece funcionalidade para obter resumos de documentos usando modelos de IA. Exemplo de uso de criação de um cliente OpenAI, configuração de opções e uso do copiloto de resumo. |
| [OpenAISummaryCopilotOptions](./openaisummarycopilotoptions/) | Representa as opções para configurar o OpenAICopilot. |
| [PdfDocument](./pdfdocument/) | Representa um documento PDF com um nome. |
| [RequiredAction](./requiredaction/) | Detalhes sobre a ação necessária para continuar a execução. Será nulo se nenhuma ação for necessária. |
| [ResponseFormat](./responseformat/) | Representa o formato de uma resposta, que pode ser um valor de string ou um valor de objeto. |
| [RunCreateRequest](./runcreaterequest/) | Representa uma solicitação para criar uma execução. |
| [RunListQueryParameters](./runlistqueryparameters/) | Objeto de parâmetros de consulta para listar execuções. |
| [RunListResponse](./runlistresponse/) | Representa uma resposta de lista contendo dados de execução. |
| [RunModifyRequest](./runmodifyrequest/) | Representa uma solicitação para modificar uma execução. |
| [RunResponse](./runresponse/) | Representa uma execução em uma thread. |
| [RunStepDetails](./runstepdetails/) | Os detalhes do passo da execução. |
| [RunStepListQueryParameters](./runsteplistqueryparameters/) | Objeto de parâmetros de consulta para listar passos de execução. |
| [RunStepListResponse](./runsteplistresponse/) | Representa uma resposta de lista contendo dados de passos de execução. |
| [RunStepResponse](./runstepresponse/) | Representa um passo na execução de uma execução. |
| [RunThreadCreateRequest](./runthreadcreaterequest/) | Representa uma solicitação para criar uma thread e executá-la em uma única solicitação. |
| [SubmitToolOutputs](./submittooloutputs/) | Representa detalhes sobre as saídas da ferramenta necessárias para que a execução continue. |
| [TextDocument](./textdocument/) | Representa um documento de texto com um nome e conteúdo. |
| [TextResponse](./textresponse/) | Representa o conteúdo de texto que faz parte de uma mensagem. |
| [ThreadCreateRequest](./threadcreaterequest/) | Representa uma solicitação para criar uma thread. |
| [ThreadMessageCreateRequest](./threadmessagecreaterequest/) | Representa uma solicitação para criar uma mensagem dentro de uma thread. |
| [ThreadMessageListQueryParameters](./threadmessagelistqueryparameters/) | Objeto de parâmetros de consulta para listar mensagens de thread. |
| [ThreadMessageListResponse](./threadmessagelistresponse/) | Representa uma resposta de lista contendo dados de mensagens de thread. |
| [ThreadMessageModifyRequest](./threadmessagemodifyrequest/) | Representa uma solicitação para modificar uma mensagem dentro de uma thread. |
| [ThreadMessageResponse](./threadmessageresponse/) | Representa uma mensagem dentro de uma thread. |
| [ThreadModifyRequest](./threadmodifyrequest/) | Representa uma solicitação para modificar uma thread. |
| [ThreadResponse](./threadresponse/) | Representa uma thread que contém mensagens. |
| [Tool](./tool/) | Representa uma ferramenta que pode ser chamada pelo modelo. |
| [ToolCall](./toolcall/) | Representa uma chamada de ferramenta dentro de uma mensagem. |
| [ToolChoice](./toolchoice/) | Representa a ToolChoice, que pode ser um valor de string ou um valor de objeto. |
| [ToolResources](./toolresources/) | Representa um conjunto de recursos que são usados pelas ferramentas do assistente. Os recursos são específicos para o tipo de ferramenta. Por exemplo, a ferramenta code_interpreter requer uma lista de IDs de arquivos, enquanto a ferramenta file_search requer uma lista de IDs de armazenamento de vetores. |
| [TruncationStrategy](./truncationstrategy/) | Representa a estratégia de truncamento que controla como uma thread será truncada antes da execução. |
| [Usage](./usage/) | Representa estatísticas de uso para uma solicitação. |
| [VectorStore](./vectorstore/) | Um auxiliar para criar um armazenamento de vetores com file_ids e anexá-lo a esta thread. Pode haver no máximo 1 armazenamento de vetores anexado à thread. |
| [VectorStoreCreateRequest](./vectorstorecreaterequest/) | Criar uma solicitação de armazenamento de vetores. |
| [VectorStoreFileBatchCreateRequest](./vectorstorefilebatchcreaterequest/) | Criar uma solicitação de lote de arquivos de armazenamento de vetores. |
| [VectorStoreFileBatchFileListQueryParameters](./vectorstorefilebatchfilelistqueryparameters/) | Objeto de parâmetros de consulta para listar arquivos de lote de armazenamento de vetores. |
| [VectorStoreFileBatchFileListResponse](./vectorstorefilebatchfilelistresponse/) | Representa uma resposta de lista contendo dados de lote de arquivos de armazenamento de vetores. |
| [VectorStoreFileBatchResponse](./vectorstorefilebatchresponse/) | O objeto de resposta de lote de arquivos de armazenamento de vetores. |
| [VectorStoreFileCreateRequest](./vectorstorefilecreaterequest/) | Criar uma solicitação de arquivo de armazenamento de vetores. |
| [VectorStoreFileListQueryParameters](./vectorstorefilelistqueryparameters/) | Objeto de parâmetros de consulta para listar arquivos de armazenamento de vetores. |
| [VectorStoreFileListResponse](./vectorstorefilelistresponse/) | Representa uma resposta de lista contendo dados de arquivos de armazenamento de vetores. |
| [VectorStoreFileResponse](./vectorstorefileresponse/) | Uma resposta de arquivo de armazenamento de vetores. |
| [VectorStoreListQueryParameters](./vectorstorelistqueryparameters/) | Objeto de parâmetros de consulta para listar armazenamentos de vetores. |
| [VectorStoreListResponse](./vectorstorelistresponse/) | Representa uma resposta de lista contendo dados de armazenamento de vetores. |
| [VectorStoreModifyRequest](./vectorstoremodifyrequest/) | Solicitação para modificar um armazenamento de vetores. |
| [VectorStoreResponse](./vectorstoreresponse/) | O objeto de armazenamento de vetores. |
## Interfaces

| Interface | Descrição |
| --- | --- |
| [IAIClient](./iaiclient/) | Representa uma interface para um cliente de IA. |
| [IAICopilot](./iaicopilot/) | Representa um copiloto para interações de IA. |
| [IChatClient&lt;TOptions&gt;](./ichatclient-1/) | Representa uma interface para um cliente de chat com opções específicas. |
| [IChatCopilot](./ichatcopilot/) | Representa um copiloto de chat para interagir com documentos via modelos de IA. |
| [IChatCopilotOptions&lt;TOptions&gt;](./ichatcopilotoptions-1/) | Representa uma interface para opções de copiloto de chat com um tipo específico. |
| [IEntityId](./ientityid/) | Representa uma entidade com um ID. |
| [IImageDescriptionClient&lt;TOptions&gt;](./iimagedescriptionclient-1/) | Representa uma interface para um cliente de descrição de imagem com opções específicas. |
| [IImageDescriptionCopilot](./iimagedescriptioncopilot/) | Representa um copiloto de descrição de imagem para extrair descrições de imagem usando modelos de IA. |
| [IImageDescriptionCopilotOptions&lt;TOptions&gt;](./iimagedescriptioncopilotoptions-1/) | Representa uma interface para opções de copiloto de descrição de imagem com um tipo específico. |
| [ILlamaClient](./illamaclient/) | Representa uma interface de cliente para interagir com a API Llama. |
| [IOpenAIClient](./iopenaiclient/) | Representa uma interface de cliente para interagir com a API OpenAI, estendendo as funcionalidades básicas do cliente de IA. |
| [IQueryParameters](./iqueryparameters/) | Representa parâmetros de consulta para solicitações da API. |
| [IStatus](./istatus/) | Representa o status de uma operação. |
| [IStringOrObject&lt;T&gt;](./istringorobject-1/) | Representa um objeto que pode ser um valor de string ou um valor de objeto. |
| [ISummaryClient&lt;TOptions&gt;](./isummaryclient-1/) | Representa uma interface para um cliente de resumo com opções específicas. |
| [ISummaryCopilot](./isummarycopilot/) | Representa um copiloto de resumo para gerar resumos para documentos usando modelos de IA. |
| [ISummaryCopilotOptions&lt;TOptions&gt;](./isummarycopilotoptions-1/) | Representa uma interface para opções de copiloto de resumo com um tipo específico. |