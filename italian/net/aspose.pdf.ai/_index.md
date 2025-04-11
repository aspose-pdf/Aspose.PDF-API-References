---
title: Aspose.Pdf.AI
second_title: Aspose.PDF for .NET API Reference
description: Il namespace Aspose.Pdf.AI fornisce classi per funzionalità AI, inclusi client API e assistenti intelligenti
type: docs
weight: 40
url: /it/net/aspose.pdf.ai/
---
Il **namespace Aspose.Pdf.AI** fornisce classi per funzionalità AI, inclusi client API e assistenti intelligenti.

## Classi

| Classe | Descrizione |
| --- | --- |
| [AIClientBase](./aiclientbase/) | Rappresenta un client per accedere all'API AI. |
| [AIClientException](./aiclientexception/) | Rappresenta un'eccezione specifica per le operazioni del client AI. |
| [AICopilotException](./aicopilotexception/) | Rappresenta un'eccezione specifica per le operazioni dei Copiloti. |
| [AICopilotFactory](./aicopilotfactory/) | Classe factory per creare diversi tipi di copiloti. |
| [Annotation](./annotation/) | Rappresenta il contenuto testuale che fa parte di un messaggio. |
| [AssistantCreateRequest](./assistantcreaterequest/) | Oggetto richiesta per creare un assistente. |
| [AssistantListQueryParameters](./assistantlistqueryparameters/) | Rappresenta l'oggetto dei parametri di query per elencare gli assistenti. |
| [AssistantListResponse](./assistantlistresponse/) | Rappresenta la risposta contenente un elenco di risposte degli assistenti. |
| [AssistantModifyRequest](./assistantmodifyrequest/) | Oggetto richiesta per modificare un assistente. |
| [AssistantResponse](./assistantresponse/) | Rappresenta un assistente che può chiamare il modello e utilizzare strumenti. |
| [Attachment](./attachment/) | Rappresenta un elenco di file allegati al messaggio e gli strumenti a cui dovrebbero essere aggiunti. |
| [BaseListQueryParameters](./baselistqueryparameters/) | Parametri di query di base per elencare oggetti. |
| [BaseResponse](./baseresponse/) | Classe base per le risposte API. |
| [CancellationTokenExtensions](./cancellationtokenextensions/) | Fornisce metodi di estensione per CancellationToken. |
| [ChatMessage](./chatmessage/) | Un messaggio di completamento della chat generato dal modello. |
| [Choice](./choice/) | Rappresenta una scelta in una risposta di completamento della chat. |
| [CodeInterpreter](./codeinterpreter/) | Rappresenta le risorse dello strumento interprete di codice. |
| [CompletionCreateRequest](./completioncreaterequest/) | Rappresenta una richiesta per l'endpoint Crea Completamento Chat. |
| [CompletionFunction](./completionfunction/) | Rappresenta l'oggetto funzione. |
| [CompletionResponse](./completionresponse/) | Rappresenta una risposta di completamento della chat restituita dal modello, basata sull'input fornito. |
| [CreateChatCompletionChunkResponse](./createchatcompletionchunkresponse/) | Rappresenta un chunk in streaming di una risposta di completamento della chat restituita dal modello, basata sull'input fornito. |
| [CreateEmbeddingRequest](./createembeddingrequest/) | Rappresenta una richiesta per l'endpoint Crea Embeddings. |
| [CreateEmbeddingResponse](./createembeddingresponse/) | Rappresenta una risposta dall'endpoint Crea Embeddings. |
| [CreateFineTuningJobRequest](./createfinetuningjobrequest/) | Rappresenta una richiesta per l'endpoint Crea Lavoro di Fine-Tuning. |
| [CreateFineTuningJobResponse](./createfinetuningjobresponse/) | Rappresenta una risposta dall'endpoint Crea Lavoro di Fine-Tuning. |
| [DataResponse&lt;T&gt;](./dataresponse-1/) | Rappresenta una risposta di dati contenente i dati specificati. |
| [DeleteStatusResponse](./deletestatusresponse/) | Rappresenta lo stato di una cancellazione di oggetto. |
| [DocumentCollection](./documentcollection/) | Rappresenta una collezione di documenti da elaborare. |
| [Embedding](./embedding/) | Rappresenta un vettore di embedding restituito dall'endpoint di embedding. |
| [Error](./error/) | Rappresenta un errore nella risposta API. |
| [ExpiresAfter](./expiresafter/) | Rappresenta la politica di scadenza per un archivio di vettori. |
| [FileCitation](./filecitation/) | Rappresenta la citazione del file. |
| [FileContentResponse&lt;T&gt;](./filecontentresponse-1/) |  |
| [FileCounts](./filecounts/) |  |
| [FileListResponse](./filelistresponse/) | Rappresenta una risposta di elenco file contenente un elenco di risposte file. |
| [FileResponse](./fileresponse/) | L'oggetto FileResponse rappresenta un documento che è stato caricato su OpenAI. |
| [FileSearch](./filesearch/) | Rappresenta le risorse dello strumento di ricerca file. |
| [Function](./function/) | Rappresenta una funzione che può essere chiamata dal modello. |
| [Hyperparameters](./hyperparameters/) | Rappresenta gli iperparametri utilizzati per un lavoro di fine-tuning. |
| [ImageDescription](./imagedescription/) | Rappresenta una descrizione dell'immagine. |
| [ImageDescriptionResult](./imagedescriptionresult/) | Rappresenta la risposta contenente le descrizioni delle immagini. |
| [ImageFile](./imagefile/) | Rappresenta un file immagine nel contenuto di un messaggio. |
| [ImageUrl](./imageurl/) | Rappresenta un URL immagine nel contenuto di un messaggio. |
| [IncompleteDetails](./incompletedetails/) | Dettagli sul perché l'esecuzione è incompleta. Sarà nullo se l'esecuzione non è incompleta. |
| [LastError](./lasterror/) | L'ultimo errore associato a questa esecuzione. Sarà nullo se non ci sono errori. |
| [ListDataResponse&lt;T&gt;](./listdataresponse-1/) | Rappresenta una risposta di dati di elenco contenente informazioni aggiuntive come i primi e ultimi ID e se ci sono più elementi. |
| [LlamaChatCompletionRequest](./llamachatcompletionrequest/) | Rappresenta il corpo della richiesta per le richieste API ChatGPT. |
| [LlamaChatCompletionResponse](./llamachatcompletionresponse/) | Rappresenta una risposta di completamento della chat restituita dal modello, basata sull'input fornito. |
| [LlamaClient](./llamaclient/) | Rappresenta un client per interagire con l'API Llama. |
| [LlamaCopilotOptionsBase](./llamacopilotoptionsbase/) | Rappresenta le opzioni di base per configurare il LlamaCopilot. |
| [LlamaModels](./llamamodels/) | Contiene costanti relative ai diversi modelli Llama. |
| [LlamaSummaryCopilot](./llamasummarycopilot/) | Fornisce funzionalità per ottenere riassunti di documenti utilizzando modelli AI. Esempio di utilizzo per creare un client Llama, configurare opzioni e utilizzare il copilota di riassunto. Nota: Questo copilota utilizza l'API di completamento, quindi la quantità totale di testo che può essere inviata è limitata dalla finestra di contesto del modello. |
| [LlamaSummaryCopilotOptions](./llamasummarycopilotoptions/) | Rappresenta le opzioni per configurare l'OpenAICopilot. |
| [Logprobs](./logprobs/) | Rappresenta informazioni sulla probabilità logaritmica per una scelta. |
| [MessageContentBase](./messagecontentbase/) | Il contenuto del messaggio in un array di testo e/o immagini. |
| [MessageContentRequest](./messagecontentrequest/) | Il contenuto del messaggio in un array di testo e/o immagini. |
| [MessageContentResponse](./messagecontentresponse/) | Il contenuto del messaggio di risposta in un array di testo e/o immagini. |
| [MessageCreation](./messagecreation/) | Rappresenta la creazione di un messaggio con il suo identificatore unico. |
| [OpenAIAssistantCopilotOptionsBase](./openaiassistantcopilotoptionsbase/) | Rappresenta le opzioni di base per configurare gli OpenAICopilots basati sull'API Assistenti. |
| [OpenAIChatCopilot](./openaichatcopilot/) | Rappresenta un copilota di chat per interagire con documenti tramite modelli AI. Esempio di utilizzo per creare un client OpenAI, configurare opzioni e utilizzare il ChatCopilot per interagire con le query degli utenti e gestire il contesto della conversazione. |
| [OpenAIChatCopilotOptions](./openaichatcopilotoptions/) | Rappresenta le opzioni per configurare l'OpenAICopilot. |
| [OpenAIClient](./openaiclient/) | Fornisce metodi per interagire con l'API OpenAI per gestire i batch di file dell'archivio vettori. |
| [OpenAIContext](./openaicontext/) | Rappresenta gli ID entità relativi a un assistente. |
| [OpenAICopilotOptionsBase](./openaicopilotoptionsbase/) | Rappresenta le opzioni di base per configurare l'OpenAICopilot. |
| [OpenAIImageDescriptionCopilot](./openaiimagedescriptioncopilot/) | Fornisce funzionalità di elaborazione delle immagini per la classe OpenAICopilot. Esempio di utilizzo per creare un client OpenAI, configurare le opzioni di ImageDescriptionCopilot e utilizzare il copilota per generare descrizioni di immagini e aggiungere descrizioni ai documenti allegati. |
| [OpenAIImageDescriptionCopilotExtensions](./openaiimagedescriptioncopilotextensions/) | Fornisce metodi di estensione per la classe OpenAIImageDescriptionCopilot. |
| [OpenAIImageDescriptionCopilotOptions](./openaiimagedescriptioncopilotoptions/) | Rappresenta le opzioni per configurare l'OpenAICopilot. |
| [OpenAIModels](./openaimodels/) | Contiene gli identificatori dei modelli OpenAI disponibili. |
| [OpenAISummaryCopilot](./openaisummarycopilot/) | Fornisce funzionalità per ottenere riassunti di documenti utilizzando modelli AI. Esempio di utilizzo per creare un client OpenAI, configurare opzioni e utilizzare il copilota di riassunto. |
| [OpenAISummaryCopilotOptions](./openaisummarycopilotoptions/) | Rappresenta le opzioni per configurare l'OpenAICopilot. |
| [PdfDocument](./pdfdocument/) | Rappresenta un documento PDF con un nome. |
| [RequiredAction](./requiredaction/) | Dettagli sull'azione richiesta per continuare l'esecuzione. Sarà nullo se non è richiesta alcuna azione. |
| [ResponseFormat](./responseformat/) | Rappresenta il formato di una risposta, che può essere un valore stringa o un valore oggetto. |
| [RunCreateRequest](./runcreaterequest/) | Rappresenta una richiesta per creare un'esecuzione. |
| [RunListQueryParameters](./runlistqueryparameters/) | Oggetto parametri di query per elencare le esecuzioni. |
| [RunListResponse](./runlistresponse/) | Rappresenta una risposta di elenco contenente dati di esecuzione. |
| [RunModifyRequest](./runmodifyrequest/) | Rappresenta una richiesta per modificare un'esecuzione. |
| [RunResponse](./runresponse/) | Rappresenta un'esecuzione su un thread. |
| [RunStepDetails](./runstepdetails/) | I dettagli del passo di esecuzione. |
| [RunStepListQueryParameters](./runsteplistqueryparameters/) | Oggetto parametri di query per elencare i passi di esecuzione. |
| [RunStepListResponse](./runsteplistresponse/) | Rappresenta una risposta di elenco contenente dati sui passi di esecuzione. |
| [RunStepResponse](./runstepresponse/) | Rappresenta un passo nell'esecuzione di un'esecuzione. |
| [RunThreadCreateRequest](./runthreadcreaterequest/) | Rappresenta una richiesta per creare un thread e eseguirlo in un'unica richiesta. |
| [SubmitToolOutputs](./submittooloutputs/) | Rappresenta dettagli sugli output degli strumenti necessari affinché l'esecuzione continui. |
| [TextDocument](./textdocument/) | Rappresenta un documento di testo con un nome e contenuto. |
| [TextResponse](./textresponse/) | Rappresenta il contenuto testuale che fa parte di un messaggio. |
| [ThreadCreateRequest](./threadcreaterequest/) | Rappresenta una richiesta per creare un thread. |
| [ThreadMessageCreateRequest](./threadmessagecreaterequest/) | Rappresenta una richiesta per creare un messaggio all'interno di un thread. |
| [ThreadMessageListQueryParameters](./threadmessagelistqueryparameters/) | Oggetto parametri di query per elencare i messaggi del thread. |
| [ThreadMessageListResponse](./threadmessagelistresponse/) | Rappresenta una risposta di elenco contenente dati sui messaggi del thread. |
| [ThreadMessageModifyRequest](./threadmessagemodifyrequest/) | Rappresenta una richiesta per modificare un messaggio all'interno di un thread. |
| [ThreadMessageResponse](./threadmessageresponse/) | Rappresenta un messaggio all'interno di un thread. |
| [ThreadModifyRequest](./threadmodifyrequest/) | Rappresenta una richiesta per modificare un thread. |
| [ThreadResponse](./threadresponse/) | Rappresenta un thread che contiene messaggi. |
| [Tool](./tool/) | Rappresenta uno strumento che può essere chiamato dal modello. |
| [ToolCall](./toolcall/) | Rappresenta una chiamata a uno strumento all'interno di un messaggio. |
| [ToolChoice](./toolchoice/) | Rappresenta la ToolChoice, che può essere un valore stringa o un valore oggetto. |
| [ToolResources](./toolresources/) | Rappresenta un insieme di risorse utilizzate dagli strumenti dell'assistente. Le risorse sono specifiche per il tipo di strumento. Ad esempio, lo strumento code_interpreter richiede un elenco di ID file, mentre lo strumento file_search richiede un elenco di ID di archivi vettori. |
| [TruncationStrategy](./truncationstrategy/) | Rappresenta la strategia di troncamento che controlla come un thread sarà troncato prima dell'esecuzione. |
| [Usage](./usage/) | Rappresenta le statistiche di utilizzo per una richiesta. |
| [VectorStore](./vectorstore/) | Un aiuto per creare un archivio di vettori con file_ids e allegarlo a questo thread. Può esserci un massimo di 1 archivio di vettori allegato al thread. |
| [VectorStoreCreateRequest](./vectorstorecreaterequest/) | Crea una richiesta di archivio di vettori. |
| [VectorStoreFileBatchCreateRequest](./vectorstorefilebatchcreaterequest/) | Crea una richiesta di batch di file di archivio di vettori. |
| [VectorStoreFileBatchFileListQueryParameters](./vectorstorefilebatchfilelistqueryparameters/) | Oggetto parametri di query per elencare i file batch di archivio di vettori. |
| [VectorStoreFileBatchFileListResponse](./vectorstorefilebatchfilelistresponse/) | Rappresenta una risposta di elenco contenente dati batch di file di archivio di vettori. |
| [VectorStoreFileBatchResponse](./vectorstorefilebatchresponse/) | L'oggetto di risposta batch di file di archivio di vettori. |
| [VectorStoreFileCreateRequest](./vectorstorefilecreaterequest/) | Crea una richiesta di file di archivio di vettori. |
| [VectorStoreFileListQueryParameters](./vectorstorefilelistqueryparameters/) | Oggetto parametri di query per elencare i file di archivio di vettori. |
| [VectorStoreFileListResponse](./vectorstorefilelistresponse/) | Rappresenta una risposta di elenco contenente dati sui file di archivio di vettori. |
| [VectorStoreFileResponse](./vectorstorefileresponse/) | Una risposta di file di archivio di vettori. |
| [VectorStoreListQueryParameters](./vectorstorelistqueryparameters/) | Oggetto parametri di query per elencare gli archivi di vettori. |
| [VectorStoreListResponse](./vectorstorelistresponse/) | Rappresenta una risposta di elenco contenente dati sugli archivi di vettori. |
| [VectorStoreModifyRequest](./vectorstoremodifyrequest/) | Modifica una richiesta di archivio di vettori. |
| [VectorStoreResponse](./vectorstoreresponse/) | L'oggetto dell'archivio di vettori. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IAIClient](./iaiclient/) | Rappresenta un'interfaccia per un client AI. |
| [IAICopilot](./iaicopilot/) | Rappresenta un copilota per interazioni AI. |
| [IChatClient&lt;TOptions&gt;](./ichatclient-1/) | Rappresenta un'interfaccia per un client di chat con opzioni specifiche. |
| [IChatCopilot](./ichatcopilot/) | Rappresenta un copilota di chat per interagire con documenti tramite modelli AI. |
| [IChatCopilotOptions&lt;TOptions&gt;](./ichatcopilotoptions-1/) | Rappresenta un'interfaccia per le opzioni del copilota di chat con un tipo specifico. |
| [IEntityId](./ientityid/) | Rappresenta un'entità con un ID. |
| [IImageDescriptionClient&lt;TOptions&gt;](./iimagedescriptionclient-1/) | Rappresenta un'interfaccia per un client di descrizione immagine con opzioni specifiche. |
| [IImageDescriptionCopilot](./iimagedescriptioncopilot/) | Rappresenta un copilota di descrizione immagine per estrarre descrizioni di immagini utilizzando modelli AI. |
| [IImageDescriptionCopilotOptions&lt;TOptions&gt;](./iimagedescriptioncopilotoptions-1/) | Rappresenta un'interfaccia per le opzioni del copilota di descrizione immagine con un tipo specifico. |
| [ILlamaClient](./illamaclient/) | Rappresenta un'interfaccia client per interagire con l'API Llama. |
| [IOpenAIClient](./iopenaiclient/) | Rappresenta un'interfaccia client per interagire con l'API OpenAI, estendendo le funzionalità di base del client AI. |
| [IQueryParameters](./iqueryparameters/) | Rappresenta i parametri di query per le richieste API. |
| [IStatus](./istatus/) | Rappresenta lo stato di un'operazione. |
| [IStringOrObject&lt;T&gt;](./istringorobject-1/) | Rappresenta un oggetto che può essere un valore stringa o un valore oggetto. |
| [ISummaryClient&lt;TOptions&gt;](./isummaryclient-1/) | Rappresenta un'interfaccia per un client di riassunto con opzioni specifiche. |
| [ISummaryCopilot](./isummarycopilot/) | Rappresenta un copilota di riassunto per generare riassunti per documenti utilizzando modelli AI. |
| [ISummaryCopilotOptions&lt;TOptions&gt;](./isummarycopilotoptions-1/) | Rappresenta un'interfaccia per le opzioni del copilota di riassunto con un tipo specifico. |