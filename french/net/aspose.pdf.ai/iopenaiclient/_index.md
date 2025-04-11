---
title: Interface IOpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.AI.IOpenAIClient. Représente une interface client pour interagir avec l'API OpenAI en étendant les fonctionnalités de base du client AI
type: docs
weight: 540
url: /fr/net/aspose.pdf.ai/iopenaiclient/
---
## Interface IOpenAIClient

Représente une interface client pour interagir avec l'API OpenAI, en étendant les fonctionnalités de base du client AI.

```csharp
public interface IOpenAIClient
```

## Méthodes

| Nom | Description |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | Annule une exécution existante dans un thread de manière asynchrone. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Annule un lot de fichiers de magasin vectoriel spécifique de manière asynchrone. |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Crée un nouvel assistant de manière asynchrone. |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Crée une nouvelle complétion de manière asynchrone. |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Crée une exécution dans un thread spécifié de manière asynchrone. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Crée un thread et une exécution à l'intérieur de celui-ci de manière asynchrone. |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Crée un nouveau thread de manière asynchrone. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Crée un nouveau message dans un thread de manière asynchrone. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Crée un nouveau magasin vectoriel et attend qu'il soit complété de manière asynchrone. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Crée un nouveau magasin vectoriel de manière asynchrone. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Crée un nouveau fichier de magasin vectoriel de manière asynchrone. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Crée un nouveau lot de fichiers de magasin vectoriel de manière asynchrone. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | Supprime un assistant existant de manière asynchrone. |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | Supprime un fichier spécifique de manière asynchrone. |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | Supprime un thread existant de manière asynchrone. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Supprime un message dans un thread de manière asynchrone. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Supprime un magasin vectoriel de manière asynchrone. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Supprime un fichier dans un magasin vectoriel de manière asynchrone. |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | Récupère les détails d'un assistant spécifique de manière asynchrone. |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Récupère une liste d'assistants de manière asynchrone. |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | Récupère les détails d'un fichier spécifique de manière asynchrone. |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | Récupère une liste de fichiers de manière asynchrone en fonction de l'objectif spécifié. |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | Récupère les détails d'une exécution spécifique dans un thread de manière asynchrone. |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Récupère une liste d'exécutions pour un thread spécifié de manière asynchrone. |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Récupère les détails d'une étape spécifique dans une exécution de manière asynchrone. |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Récupère une liste d'étapes pour une exécution spécifique dans un thread de manière asynchrone. |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | Récupère les détails d'un thread spécifique de manière asynchrone. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string) | Récupère les détails d'un message spécifique dans un thread de manière asynchrone. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Récupère une liste de messages pour un thread spécifique de manière asynchrone. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | Récupère les détails d'un magasin vectoriel spécifique de manière asynchrone. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Récupère les détails d'un fichier spécifique dans un magasin vectoriel de manière asynchrone. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Récupère les détails d'un lot de fichiers de magasin vectoriel spécifique de manière asynchrone. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Récupère une liste de fichiers dans un lot de fichiers de magasin vectoriel spécifique de manière asynchrone. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Récupère une liste de fichiers dans un magasin vectoriel spécifique de manière asynchrone. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Récupère une liste de magasins vectoriels de manière asynchrone. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifie un assistant existant de manière asynchrone. |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifie une exécution existante dans un thread de manière asynchrone. |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifie un thread existant de manière asynchrone. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifie un message existant dans un thread de manière asynchrone. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifie un magasin vectoriel existant de manière asynchrone. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Exécute l'assistant avec le threadId spécifié et le runCreateRequest, et obtient de manière asynchrone la réponse de l'assistant. |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Télécharge un fichier de manière asynchrone sur le serveur OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Attend le premier message de l'assistant dans un thread de manière asynchrone. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Attend qu'une exécution soit complétée dans un thread de manière asynchrone. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Attend qu'un message de thread spécifique soit complété de manière asynchrone. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Attend qu'un fichier de magasin vectoriel spécifique soit complété de manière asynchrone. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Attend qu'un magasin vectoriel spécifique soit complété de manière asynchrone. |

### Voir aussi

* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)