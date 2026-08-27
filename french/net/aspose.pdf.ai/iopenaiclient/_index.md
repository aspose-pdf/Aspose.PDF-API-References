---
title: "Interface IOpenAIClient"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Interface Aspose.Pdf.AI.IOpenAIClient. Représente une interface client pour interagir avec l'API OpenAI, étendant les fonctionnalités de base du client IA."
type: docs
weight: 590
url: /fr/net/aspose.pdf.ai/iopenaiclient/
---
## IOpenAIClient interface

Représente une interface client pour interagir avec l'API OpenAI, en étendant les fonctionnalités de base du client IA.

```csharp
public interface IOpenAIClient
```

## Méthodes

| Nom | Description |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | Annule de manière asynchrone une exécution existante au sein d'un fil. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Annule de manière asynchrone un lot de fichiers de magasin vectoriel spécifique. |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Crée de manière asynchrone un nouvel assistant. |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Crée une nouvelle complétion de façon asynchrone. |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Crée une exécution dans un fil spécifié de façon asynchrone. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Crée un fil et une exécution à l'intérieur de celui-ci de façon asynchrone. |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Crée un nouveau fil de façon asynchrone. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Crée un nouveau message dans un fil de façon asynchrone. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Crée un nouveau magasin de vecteurs et attend qu'il se termine de façon asynchrone. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Crée un nouveau magasin de vecteurs de façon asynchrone. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Crée un nouveau fichier de magasin de vecteurs de façon asynchrone. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Crée un nouveau lot de fichiers de magasin de vecteurs de façon asynchrone. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | Supprime un assistant existant de façon asynchrone. |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | Supprime un fichier spécifique de façon asynchrone. |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | Supprime un fil existant de façon asynchrone. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Supprime un message dans un fil de façon asynchrone. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Supprime un magasin de vecteurs de façon asynchrone. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Supprime un fichier dans un magasin de vecteurs de façon asynchrone. |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | Récupère les détails d'un assistant spécifique de façon asynchrone. |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Récupère une liste d'assistants de façon asynchrone. |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | Récupère les détails d'un fichier spécifique de façon asynchrone. |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | Récupère une liste de fichiers de façon asynchrone en fonction du but spécifié. |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | Récupère les détails d'une exécution spécifique dans un fil de façon asynchrone. |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Récupère une liste d'exécutions pour un fil spécifié de façon asynchrone. |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Récupère les détails d'une étape spécifique d'une exécution de manière asynchrone. |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Récupère une liste d'étapes pour une exécution spécifique dans un fil de discussion de manière asynchrone. |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | Récupère les détails d'un fil de discussion spécifique de manière asynchrone. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Récupère les détails d'un message spécifique dans un fil de discussion de manière asynchrone. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Récupère une liste de messages pour un fil de discussion spécifique de manière asynchrone. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | Récupère les détails d'un magasin de vecteurs spécifique de manière asynchrone. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Récupère les détails d'un fichier spécifique dans un magasin de vecteurs de manière asynchrone. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Récupère les détails d'un lot de fichiers de magasin de vecteurs spécifique de manière asynchrone. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Récupère une liste de fichiers dans un lot de fichiers de magasin de vecteurs spécifique de manière asynchrone. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Récupère une liste de fichiers dans un magasin de vecteurs spécifique de manière asynchrone. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Récupère une liste de magasins de vecteurs de manière asynchrone. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifie un assistant existant de manière asynchrone. |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifie une exécution existante dans un fil de discussion de manière asynchrone. |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifie un fil de discussion existant de manière asynchrone. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifie un message existant dans un fil de discussion de manière asynchrone. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifie un magasin de vecteurs existant de manière asynchrone. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Exécute l'assistant avec le threadId spécifié et runCreateRequest, et récupère de manière asynchrone la réponse de l'assistant. |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Téléverse un fichier de manière asynchrone vers le serveur OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Attend le premier message de l'assistant dans un fil de discussion de manière asynchrone. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Attend qu'une exécution se termine dans un fil de discussion de manière asynchrone. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | Attend qu'un message de fil de discussion spécifique se termine de manière asynchrone. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | Attend qu'un fichier de magasin de vecteurs spécifique se termine de manière asynchrone. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Attend qu'un magasin de vecteurs spécifique se termine de manière asynchrone. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


