---
title: Interface IOpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Interfaccia Aspose.Pdf.AI.IOpenAIClient. Rappresenta un'interfaccia client per interagire con l'API OpenAI estendendo le funzionalità di base del client AI
type: docs
weight: 540
url: /it/net/aspose.pdf.ai/iopenaiclient/
---
## Interfaccia IOpenAIClient

Rappresenta un'interfaccia client per interagire con l'API OpenAI, estendendo le funzionalità di base del client AI.

```csharp
public interface IOpenAIClient
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | Annulla un'esecuzione esistente all'interno di un thread in modo asincrono. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Annulla un batch di file di archiviazione vettoriale specifico in modo asincrono. |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Crea un nuovo assistente in modo asincrono. |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Crea una nuova completamento in modo asincrono. |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Crea un'esecuzione all'interno di un thread specificato in modo asincrono. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Crea un thread e un'esecuzione al suo interno in modo asincrono. |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Crea un nuovo thread in modo asincrono. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Crea un nuovo messaggio all'interno di un thread in modo asincrono. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Crea un nuovo archivio vettoriale e attende che venga completato in modo asincrono. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Crea un nuovo archivio vettoriale in modo asincrono. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Crea un nuovo file di archivio vettoriale in modo asincrono. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Crea un nuovo batch di file di archiviazione vettoriale in modo asincrono. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | Elimina un assistente esistente in modo asincrono. |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | Elimina un file specifico in modo asincrono. |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | Elimina un thread esistente in modo asincrono. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Elimina un messaggio all'interno di un thread in modo asincrono. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Elimina un archivio vettoriale in modo asincrono. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Elimina un file all'interno di un archivio vettoriale in modo asincrono. |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | Recupera i dettagli di un assistente specifico in modo asincrono. |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Recupera un elenco di assistenti in modo asincrono. |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | Recupera i dettagli di un file specifico in modo asincrono. |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | Recupera un elenco di file in modo asincrono in base allo scopo specificato. |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | Recupera i dettagli di un'esecuzione specifica all'interno di un thread in modo asincrono. |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Recupera un elenco di esecuzioni per un thread specificato in modo asincrono. |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Recupera i dettagli di un passo specifico all'interno di un'esecuzione in modo asincrono. |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Recupera un elenco di passi per un'esecuzione specifica all'interno di un thread in modo asincrono. |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | Recupera i dettagli di un thread specifico in modo asincrono. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Recupera i dettagli di un messaggio specifico all'interno di un thread in modo asincrono. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Recupera un elenco di messaggi per un thread specifico in modo asincrono. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | Recupera i dettagli di un archivio vettoriale specifico in modo asincrono. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Recupera i dettagli di un file specifico all'interno di un archivio vettoriale in modo asincrono. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Recupera i dettagli di un batch di file di archiviazione vettoriale specifico in modo asincrono. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Recupera un elenco di file all'interno di un batch di file di archiviazione vettoriale specifico in modo asincrono. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Recupera un elenco di file all'interno di un archivio vettoriale specifico in modo asincrono. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Recupera un elenco di archivi vettoriali in modo asincrono. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifica un assistente esistente in modo asincrono. |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifica un'esecuzione esistente all'interno di un thread in modo asincrono. |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifica un thread esistente in modo asincrono. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifica un messaggio esistente all'interno di un thread in modo asincrono. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifica un archivio vettoriale esistente in modo asincrono. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Esegue l'assistente con il threadId specificato e runCreateRequest, e ottiene in modo asincrono la risposta dell'assistente. |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Carica un file in modo asincrono sul server OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Attende il primo messaggio dall'assistente all'interno di un thread in modo asincrono. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Attende che un'esecuzione venga completata all'interno di un thread in modo asincrono. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Attende che un messaggio specifico del thread venga completato in modo asincrono. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Attende che un file specifico di archiviazione vettoriale venga completato in modo asincrono. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Attende che un archivio vettoriale specifico venga completato in modo asincrono. |

### Vedi Anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)