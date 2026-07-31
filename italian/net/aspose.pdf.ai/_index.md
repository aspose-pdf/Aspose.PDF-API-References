---
title: "Aspose.Pdf.AI"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Il namespace Aspose.Pdf.AI fornisce classi per funzionalità AI includendo client API e assistenti intelligenti."
type: docs
weight: 40
url: /it/net/aspose.pdf.ai/
---
Lo spazio dei nomi **Aspose.Pdf.AI** fornisce classi per le funzionalità di IA, inclusi client API e assistenti intelligenti.

## Classi

| Classe | Descrizione |
| --- | --- |
| [AIClientBase](./aiclientbase/) | Rappresenta il client per accedere all'API AI. |
| [AIClientException](./aiclientexception/) | Rappresenta un'eccezione specifica per le operazioni del client AI. |
| [AICopilotException](./aicopilotexception/) | Rappresenta un'eccezione specifica per le operazioni dei Copilots. |
| [AICopilotFactory](./aicopilotfactory/) | Classe Factory per creare diversi tipi di copilots. |
| [Annotation](./annotation/) | Rappresenta il contenuto testuale che fa parte di un messaggio. |
| [AssistantCreateRequest](./assistantcreaterequest/) | Oggetto di richiesta per la creazione di un assistente. |
| [AssistantListQueryParameters](./assistantlistqueryparameters/) | Rappresenta l'oggetto dei parametri di query per l'elenco degli assistenti. |
| [AssistantListResponse](./assistantlistresponse/) | Rappresenta la risposta contenente un elenco di risposte dell'assistente. |
| [AssistantModifyRequest](./assistantmodifyrequest/) | Oggetto di richiesta per la modifica di un assistente. |
| [AssistantResponse](./assistantresponse/) | Rappresenta un assistente che può chiamare il modello e utilizzare gli strumenti. |
| [Attachment](./attachment/) | Rappresenta un elenco di file allegati al messaggio e gli strumenti a cui dovrebbero essere aggiunti. |
| [BaseListQueryParameters](./baselistqueryparameters/) | Parametri di query di base per l'elenco degli oggetti. |
| [BaseResponse](./baseresponse/) | Classe base per le risposte API. |
| [CancellationTokenExtensions](./cancellationtokenextensions/) | Fornisce metodi di estensione per CancellationToken. |
| [ChatMessage](./chatmessage/) | Un messaggio di completamento della chat generato dal modello. |
| [ChatMessageResponse](./chatmessageresponse/) | Un messaggio di completamento della chat generato dal modello. |
| [Choice](./choice/) | Rappresenta una scelta in una risposta di completamento della chat. |
| [CodeInterpreter](./codeinterpreter/) | Rappresenta le risorse dello strumento interprete di codice. |
| [CompletionCreateRequest](./completioncreaterequest/) | Rappresenta una richiesta per il endpoint Create Chat Completion. |
| [CompletionFunction](./completionfunction/) | Rappresenta l'oggetto funzione. |
| [CompletionResponse](./completionresponse/) | Rappresenta una risposta di completamento della chat restituita dal modello, basata sull'input fornito. |
| [CreateChatCompletionChunkResponse](./createchatcompletionchunkresponse/) | Rappresenta un blocco in streaming di una risposta di completamento della chat restituita dal modello, basato sull'input fornito. |
| [CreateEmbeddingRequest](./createembeddingrequest/) | Rappresenta una richiesta per il endpoint Create Embeddings. |
| [CreateEmbeddingResponse](./createembeddingresponse/) | Rappresenta una risposta dal endpoint Create Embeddings. |
| [CreateFineTuningJobRequest](./createfinetuningjobrequest/) | Rappresenta una richiesta per il endpoint Create Fine-Tuning Job. |
| [CreateFineTuningJobResponse](./createfinetuningjobresponse/) | Rappresenta una risposta dal endpoint Create Fine-Tuning Job. |
| [DataResponse&lt;T&gt;](./dataresponse-1/) | Rappresenta una risposta dati contenente i dati specificati. |
| [DeleteStatusResponse](./deletestatusresponse/) | Rappresenta lo stato di una cancellazione di oggetto. |
| [DocumentCollection](./documentcollection/) | Rappresenta una raccolta di documenti da elaborare. |
| [Embedding](./embedding/) | Rappresenta un vettore di embedding restituito dal endpoint embedding. |
| [Error](./error/) | Rappresenta un errore nella risposta API. |
| [ExpiresAfter](./expiresafter/) | Rappresenta la politica di scadenza per un archivio vettoriale. |
| [FileCitation](./filecitation/) | Rappresenta la citazione del file. |
| [FileContentResponse&lt;T&gt;](./filecontentresponse-1/) |  |
| [FileCounts](./filecounts/) |  |
| [FileListResponse](./filelistresponse/) | Rappresenta una risposta di elenco file contenente una lista di risposte file. |
| [FileResponse](./fileresponse/) | L'oggetto FileResponse rappresenta un documento che è stato caricato su OpenAI. |
| [FileSearch](./filesearch/) | Rappresenta le risorse dello strumento di ricerca file. |
| [Function](./function/) | Rappresenta una funzione che può essere chiamata dal modello. |
| [Hyperparameters](./hyperparameters/) | Rappresenta gli iperparametri utilizzati per un lavoro di fine-tuning. |
| [ImageDescription](./imagedescription/) | Rappresenta una descrizione dell'immagine. |
| [ImageDescriptionResult](./imagedescriptionresult/) | Rappresenta la risposta contenente descrizioni delle immagini. |
| [ImageFile](./imagefile/) | Rappresenta un file immagine nel contenuto di un messaggio. |
| [ImageUrl](./imageurl/) | Rappresenta un URL immagine nel contenuto di un messaggio. |
| [IncompleteDetails](./incompletedetails/) | Dettagli sul motivo per cui l'esecuzione è incompleta. Sarà null se l'esecuzione non è incompleta. |
| [LastError](./lasterror/) | L'ultimo errore associato a questa esecuzione. Sarà null se non ci sono errori. |
| [ListDataResponse&lt;T&gt;](./listdataresponse-1/) | Rappresenta una risposta di dati elenco contenente informazioni aggiuntive come ID iniziale e finale e se ci sono altri elementi. |
| [LlamaChatCompletionRequest](./llamachatcompletionrequest/) | Rappresenta il corpo della richiesta per le richieste API di ChatGPT. |
| [LlamaChatCompletionResponse](./llamachatcompletionresponse/) | Rappresenta una risposta di completamento della chat restituita dal modello, basata sull'input fornito. |
| [LlamaClient](./llamaclient/) | Rappresenta un client per interagire con l'API Llama. |
| [LlamaCopilotOptionsBase](./llamacopilotoptionsbase/) | Rappresenta le opzioni di base per configurare LlamaCopilot. |
| [LlamaModels](./llamamodels/) | Contiene costanti relative a diversi modelli Llama. |
| [LlamaSummaryCopilot](./llamasummarycopilot/) | Fornisce funzionalità per ottenere riepiloghi di documenti utilizzando modelli AI. Esempio di utilizzo per creare un client Llama, configurare le opzioni e utilizzare il copilot di riepilogo. Nota: questo copilot utilizza l'API di completamento, quindi la quantità totale di testo che può essere inviata è limitata dalla finestra di contesto del modello. |
| [LlamaSummaryCopilotOptions](./llamasummarycopilotoptions/) | Rappresenta le opzioni per configurare OpenAICopilot. |
| [Logprobs](./logprobs/) | Rappresenta le informazioni di probabilità logaritmica per una scelta. |
| [MessageContentBase](./messagecontentbase/) | Il contenuto del messaggio in un array di testo e/o immagini. |
| [MessageContentRequest](./messagecontentrequest/) | Il contenuto del messaggio in un array di testo e/o immagini. |
| [MessageContentResponse](./messagecontentresponse/) | Il contenuto del messaggio di risposta in un array di testo e/o immagini. |
| [MessageCreation](./messagecreation/) | Rappresenta la creazione di un messaggio con il suo identificatore unico. |
| [OcrDetail](./ocrdetail/) | Rappresenta il risultato OCR per una singola pagina di un documento o un singolo file immagine. |
| [OpenAIAssistantCopilotOptionsBase](./openaiassistantcopilotoptionsbase/) | Rappresenta le opzioni di base per configurare gli OpenAICopilots basati sull'API Assistants. |
| [OpenAIChatCopilot](./openaichatcopilot/) | Rappresenta un copilot di chat per interagire con i documenti tramite modelli AI. Esempio di utilizzo per creare un client OpenAI, configurare le opzioni e utilizzare il ChatCopilot per interagire con le richieste degli utenti e gestire il contesto della conversazione. |
| [OpenAIChatCopilotOptions](./openaichatcopilotoptions/) | Rappresenta le opzioni per configurare OpenAICopilot. |
| [OpenAIClient](./openaiclient/) | Fornisce metodi per interagire con l'API OpenAI per gestire i batch di file del vector store. |
| [OpenAIContext](./openaicontext/) | Rappresenta gli ID delle entità relativi a un assistente. |
| [OpenAICopilotOptionsBase](./openaicopilotoptionsbase/) | Rappresenta le opzioni di base per configurare l'OpenAICopilot. |
| [OpenAIImageDescriptionCopilot](./openaiimagedescriptioncopilot/) | Fornisce funzionalità di elaborazione immagini per la classe OpenAICopilot. Esempio di utilizzo per creare un client OpenAI, configurare le opzioni di ImageDescriptionCopilot e utilizzare il copilot per generare descrizioni delle immagini e aggiungere descrizioni ai documenti allegati. |
| [OpenAIImageDescriptionCopilotExtensions](./openaiimagedescriptioncopilotextensions/) | Fornisce metodi di estensione per la classe OpenAIImageDescriptionCopilot. |
| [OpenAIImageDescriptionCopilotOptions](./openaiimagedescriptioncopilotoptions/) | Rappresenta le opzioni per configurare OpenAICopilot. |
| [OpenAIModels](./openaimodels/) | Contiene gli identificatori dei modelli OpenAI disponibili. |
| [OpenAIOcrCopilot](./openaiocrcopilot/) | Fornisce capacità OCR per estrarre testo da documenti PDF e immagini. I tipi di immagine supportati: PNG (.png), JPEG (.jpeg e .jpg), WEBP (.webp), GIF non animata (.gif). Esempio di utilizzo per creare un client OpenAI, configurare le opzioni e utilizzare il copilot OCR. |
| [OpenAIOcrCopilotOptions](./openaiocrcopilotoptions/) | Rappresenta le opzioni per configurare l'OpenAIOcrCopilot. |
| [OpenAISummaryCopilot](./openaisummarycopilot/) | Fornisce funzionalità per ottenere riepiloghi dei documenti usando modelli AI. Esempio di utilizzo per creare un client OpenAI, configurare le opzioni e utilizzare il copilot di riepilogo. |
| [OpenAISummaryCopilotOptions](./openaisummarycopilotoptions/) | Rappresenta le opzioni per configurare OpenAICopilot. |
| [PdfDocument](./pdfdocument/) | Rappresenta un documento PDF con un nome. |
| [RequiredAction](./requiredaction/) | Dettagli sull'azione necessaria per continuare l'esecuzione. Sarà null se non è richiesta alcuna azione. |
| [ResponseFormat](./responseformat/) | Rappresenta il formato di una risposta, che può essere un valore stringa o un valore oggetto. |
| [RunCreateRequest](./runcreaterequest/) | Rappresenta una richiesta per creare un'esecuzione. |
| [RunListQueryParameters](./runlistqueryparameters/) | Oggetto dei parametri di query per elencare le esecuzioni. |
| [RunListResponse](./runlistresponse/) | Rappresenta una risposta di elenco contenente i dati dell'esecuzione. |
| [RunModifyRequest](./runmodifyrequest/) | Rappresenta una richiesta per modificare un'esecuzione. |
| [RunResponse](./runresponse/) | Rappresenta un'esecuzione su un thread. |
| [RunStepDetails](./runstepdetails/) | I dettagli del passaggio dell'esecuzione. |
| [RunStepListQueryParameters](./runsteplistqueryparameters/) | Oggetto dei parametri di query per elencare i passaggi dell'esecuzione. |
| [RunStepListResponse](./runsteplistresponse/) | Rappresenta una risposta di elenco contenente i dati del passaggio dell'esecuzione. |
| [RunStepResponse](./runstepresponse/) | Rappresenta un passaggio nell'esecuzione di un run. |
| [RunThreadCreateRequest](./runthreadcreaterequest/) | Rappresenta una richiesta per creare un thread ed eseguirlo in un'unica richiesta. |
| [SubmitToolOutputs](./submittooloutputs/) | Rappresenta i dettagli sugli output degli strumenti necessari per continuare l'esecuzione. |
| [TextDocument](./textdocument/) | Rappresenta un documento di testo con un nome e un contenuto. |
| [TextRecognitionResult](./textrecognitionresult/) | Rappresenta i risultati OCR aggregati per un singolo documento sorgente. |
| [TextResponse](./textresponse/) | Rappresenta il contenuto testuale che fa parte di un messaggio. |
| [ThreadCreateRequest](./threadcreaterequest/) | Rappresenta una richiesta per creare un thread. |
| [ThreadMessageCreateRequest](./threadmessagecreaterequest/) | Rappresenta una richiesta per creare un messaggio all'interno di un thread. |
| [ThreadMessageListQueryParameters](./threadmessagelistqueryparameters/) | Oggetto dei parametri di query per elencare i messaggi del thread. |
| [ThreadMessageListResponse](./threadmessagelistresponse/) | Rappresenta una risposta di elenco contenente i dati dei messaggi del thread. |
| [ThreadMessageModifyRequest](./threadmessagemodifyrequest/) | Rappresenta una richiesta per modificare un messaggio all'interno di un thread. |
| [ThreadMessageResponse](./threadmessageresponse/) | Rappresenta un messaggio all'interno di un thread. |
| [ThreadModifyRequest](./threadmodifyrequest/) | Rappresenta una richiesta per modificare un thread. |
| [ThreadResponse](./threadresponse/) | Rappresenta un thread che contiene messaggi. |
| [Tool](./tool/) | Rappresenta uno strumento che può essere chiamato dal modello. |
| [ToolCall](./toolcall/) | Rappresenta una chiamata di strumento all'interno di un messaggio. |
| [ToolChoice](./toolchoice/) | Rappresenta il ToolChoice, che può essere sia un valore stringa sia un valore oggetto. |
| [ToolResources](./toolresources/) | Rappresenta un insieme di risorse utilizzate dagli strumenti dell'assistente. Le risorse sono specifiche per il tipo di strumento. Ad esempio, lo strumento code_interpreter richiede un elenco di ID file, mentre lo strumento file_search richiede un elenco di ID di vector store. |
| [TruncationStrategy](./truncationstrategy/) | Rappresenta la strategia di troncamento che controlla come un thread verrà troncato prima dell'esecuzione. |
| [Usage](./usage/) | Rappresenta le statistiche di utilizzo per una richiesta. |
| [VectorStore](./vectorstore/) | Un helper per creare un vector store con file_ids e collegarlo a questo thread. È possibile avere al massimo 1 vector store collegato al thread. |
| [VectorStoreCreateRequest](./vectorstorecreaterequest/) | Crea una richiesta di vector store. |
| [VectorStoreFileBatchCreateRequest](./vectorstorefilebatchcreaterequest/) | Crea una richiesta di batch di file per il vector store. |
| [VectorStoreFileBatchFileListQueryParameters](./vectorstorefilebatchfilelistqueryparameters/) | Oggetto dei parametri di query per elencare i file batch del vector store. |
| [VectorStoreFileBatchFileListResponse](./vectorstorefilebatchfilelistresponse/) | Rappresenta una risposta di elenco contenente i dati del batch di file del vector store. |
| [VectorStoreFileBatchResponse](./vectorstorefilebatchresponse/) | L'oggetto di risposta del batch di file del vector store. |
| [VectorStoreFileCreateRequest](./vectorstorefilecreaterequest/) | Crea una richiesta di file per il vector store. |
| [VectorStoreFileListQueryParameters](./vectorstorefilelistqueryparameters/) | Oggetto dei parametri di query per elencare i file del vector store. |
| [VectorStoreFileListResponse](./vectorstorefilelistresponse/) | Rappresenta una risposta di elenco contenente i dati dei file del vector store. |
| [VectorStoreFileResponse](./vectorstorefileresponse/) | Una risposta di file dell'archivio vettoriale. |
| [VectorStoreListQueryParameters](./vectorstorelistqueryparameters/) | Oggetto dei parametri di query per elencare gli archivi vettoriali. |
| [VectorStoreListResponse](./vectorstorelistresponse/) | Rappresenta una risposta di elenco contenente dati dell'archivio vettoriale. |
| [VectorStoreModifyRequest](./vectorstoremodifyrequest/) | Modifica una richiesta di archivio vettoriale. |
| [VectorStoreResponse](./vectorstoreresponse/) | L'oggetto dell'archivio vettoriale. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IAIClient](./iaiclient/) | Rappresenta un'interfaccia per un client AI. |
| [IAICopilot](./iaicopilot/) | Rappresenta un copilota per le interazioni AI. |
| [IChatClient&lt;TOptions&gt;](./ichatclient-1/) | Rappresenta un'interfaccia per un client di chat con opzioni specifiche. |
| [IChatCopilot](./ichatcopilot/) | Rappresenta un copilota di chat per interagire con i documenti tramite modelli AI. |
| [IChatCopilotOptions&lt;TOptions&gt;](./ichatcopilotoptions-1/) | Rappresenta un'interfaccia per le opzioni del copilota di chat con un tipo specifico. |
| [IEntityId](./ientityid/) | Rappresenta un'entità con un ID. |
| [IImageDescriptionClient&lt;TOptions&gt;](./iimagedescriptionclient-1/) | Rappresenta un'interfaccia per un client di descrizione immagine con opzioni specifiche. |
| [IImageDescriptionCopilot](./iimagedescriptioncopilot/) | Rappresenta un copilota di descrizione immagine per estrarre descrizioni delle immagini usando modelli AI. |
| [IImageDescriptionCopilotOptions&lt;TOptions&gt;](./iimagedescriptioncopilotoptions-1/) | Rappresenta un'interfaccia per le opzioni del copilota di descrizione immagine con un tipo specifico. |
| [ILlamaClient](./illamaclient/) | Rappresenta un'interfaccia client per interagire con l'API Llama. |
| [IOcrClient&lt;TOptions&gt;](./iocrclient-1/) | Rappresenta un'interfaccia per un client OCR con opzioni specifiche. |
| [IOcrCopilot](./iocrcopilot/) | Rappresenta un copilota OCR per elaborare PDF scansionati e immagini tramite modelli AI. |
| [IOcrCopilotOptions&lt;TOptions&gt;](./iocrcopilotoptions-1/) | Rappresenta un'interfaccia per le opzioni del copilota di chat con un tipo specifico. |
| [IOpenAIClient](./iopenaiclient/) | Rappresenta un'interfaccia client per interagire con l'API OpenAI, estendendo le funzionalità di base del client AI. |
| [IQueryParameters](./iqueryparameters/) | Rappresenta i parametri di query per le richieste API. |
| [IStatus](./istatus/) | Rappresenta lo stato di un'operazione. |
| [IStringOrObject&lt;T&gt;](./istringorobject-1/) | Rappresenta un oggetto che può essere un valore stringa o un valore oggetto. |
| [ISummaryClient&lt;TOptions&gt;](./isummaryclient-1/) | Rappresenta un'interfaccia per un client di riepilogo con opzioni specifiche. |
| [ISummaryCopilot](./isummarycopilot/) | Rappresenta un copilota di riepilogo per generare riepiloghi dei documenti usando modelli AI. |
| [ISummaryCopilotOptions&lt;TOptions&gt;](./isummarycopilotoptions-1/) | Rappresenta un'interfaccia per le opzioni del copilota di riepilogo con un tipo specifico. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [Detail](./detail/) | Specifica il livello di dettaglio per l'analisi delle immagini. |


