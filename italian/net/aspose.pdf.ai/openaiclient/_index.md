---
title: "Classe OpenAIClient"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.OpenAIClient. Fornisce metodi per interagire con l'API OpenAI per la gestione dei batch di file del vector store"
type: docs
weight: 900
url: /it/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient class

Fornisce metodi per interagire con l'API OpenAI per gestire i batch di file del vector store.

Fornisce metodi per interagire con l'API OpenAI per la gestione dei file del vector store.

Fornisce metodi per interagire con l'API OpenAI per la gestione dei vector store.

Rappresenta un client per interagire con l'API OpenAI, estendendo le funzionalità di base del client AI.

Fornisce metodi per interagire con l'API OpenAI per la gestione dei passaggi di esecuzione all'interno dei thread.

Fornisce metodi per interagire con l'API OpenAI per la gestione dei file.

Fornisce metodi per interagire con l'API OpenAI per la gestione dei messaggi dei thread.

Fornisce metodi per interagire con l'API OpenAI per la gestione dei thread.

Fornisce metodi per interagire con l'API OpenAI per la gestione degli assistenti.

Fornisce un metodo per interagire con l'API OpenAI per creare completamenti.

Fornisce metodi per interagire con l'API OpenAI per la gestione delle esecuzioni all'interno dei thread.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, 
    IOcrClient<OpenAIOcrCopilotOptions>, IOpenAIClient, ISummaryClient<OpenAISummaryCopilotOptions>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Ottiene o imposta il ritardo di backoff in secondi. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Ottiene o imposta il numero massimo di tentativi di richiesta HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Ottiene o imposta l'intervallo di polling in secondi. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Ottiene o imposta il timeout di polling in secondi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Annulla in modo asincrono un'esecuzione esistente all'interno di un thread. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Annulla in modo asincrono un batch specifico di file del vector store. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Crea un nuovo assistente in modo asincrono. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Crea un nuovo completamento in modo asincrono. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Crea un run all'interno di un thread specificato in modo asincrono. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Crea un thread e un run al suo interno in modo asincrono. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Crea un nuovo thread in modo asincrono. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Crea un nuovo messaggio all'interno di un thread in modo asincrono. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Crea un nuovo archivio vettoriale e attende il completamento in modo asincrono. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Crea un nuovo archivio vettoriale in modo asincrono. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Crea un nuovo file di archivio vettoriale in modo asincrono. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Crea un nuovo batch di file di archivio vettoriale in modo asincrono. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Elimina un assistente esistente in modo asincrono. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Elimina un file specifico in modo asincrono. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Elimina un thread esistente in modo asincrono. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Elimina un messaggio all'interno di un thread in modo asincrono. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Elimina un archivio vettoriale in modo asincrono. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Elimina un file all'interno di un archivio vettoriale in modo asincrono. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Rilascia le risorse utilizzate da [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Recupera i dettagli di un assistente specifico in modo asincrono. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Recupera un elenco di assistenti in modo asincrono. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Ottiene un'istanza di [`IChatCopilot`](../ichatcopilot/) con le opzioni specificate. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Recupera i dettagli di un file specifico in modo asincrono. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Recupera un elenco di file in modo asincrono basato sullo scopo specificato. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Ottiene un'istanza di [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) con le opzioni specificate. |
| [GetOcrCopilot](../../aspose.pdf.ai/openaiclient/getocrcopilot/)(IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Ottiene un'istanza di [`IOcrCopilot`](../iocrcopilot/) con le opzioni specificate. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Recupera i dettagli di un run specifico all'interno di un thread in modo asincrono. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Recupera un elenco di run per un thread specificato in modo asincrono. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Recupera i dettagli di uno step specifico all'interno di un'esecuzione in modo asincrono. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Recupera un elenco di step per un'esecuzione specifica all'interno di un thread in modo asincrono. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Ottiene un'istanza di [`ISummaryCopilot`](../isummarycopilot/) con le opzioni specificate. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Recupera i dettagli di un thread specifico in modo asincrono. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Recupera i dettagli di un messaggio specifico all'interno di un thread in modo asincrono. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Recupera un elenco di messaggi per un thread specifico in modo asincrono. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Recupera i dettagli di un archivio vettoriale specifico in modo asincrono. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Recupera i dettagli di un file specifico all'interno di un archivio vettoriale in modo asincrono. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Recupera i dettagli di un batch di file di archivio vettoriale specifico in modo asincrono. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Recupera un elenco di file all'interno di un batch di file di archivio vettoriale specifico in modo asincrono. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Recupera un elenco di file all'interno di un archivio vettoriale specifico in modo asincrono. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Recupera un elenco di archivi vettoriali in modo asincrono. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifica un assistente esistente in modo asincrono. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifica un'esecuzione esistente all'interno di un thread in modo asincrono. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifica un thread esistente in modo asincrono. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifica un messaggio esistente all'interno di un thread in modo asincrono. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifica un archivio vettoriale esistente in modo asincrono. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Esegue l'assistente con il threadId e il runCreateRequest specificati, e ottiene in modo asincrono la risposta dell'assistente. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Carica un file in modo asincrono sul server OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Attende il primo messaggio dall'assistente all'interno di un thread in modo asincrono. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Attende che un'esecuzione termini all'interno di un thread in modo asincrono. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | Attende che un messaggio di thread specifico termini in modo asincrono. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | Attende che un file di archivio vettoriale specifico termini in modo asincrono. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Attende che un archivio vettoriale specifico termini in modo asincrono. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Crea una nuova istanza di [`Builder`](../openaiclient.builder/) con la chiave API fornita. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Classe builder per creare un'istanza di `OpenAIClient`. |

### Vedi anche

* class [AIClientBase](../aiclientbase/)
* interface [IChatClient&lt;TOptions&gt;](../ichatclient-1/)
* class [OpenAIChatCopilotOptions](../openaichatcopilotoptions/)
* interface [IImageDescriptionClient&lt;TOptions&gt;](../iimagedescriptionclient-1/)
* class [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions/)
* interface [IOcrClient&lt;TOptions&gt;](../iocrclient-1/)
* class [OpenAIOcrCopilotOptions](../openaiocrcopilotoptions/)
* interface [IOpenAIClient](../iopenaiclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


