---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.OpenAIClient. Fournit des méthodes pour interagir avec l'API OpenAI pour gérer les lots de fichiers de magasin vectoriel
type: docs
weight: 840
url: /fr/net/aspose.pdf.ai/openaiclient/
---
## Classe OpenAIClient

Fournit des méthodes pour interagir avec l'API OpenAI pour gérer les lots de fichiers de magasin vectoriel.

Fournit des méthodes pour interagir avec l'API OpenAI pour gérer les fichiers de magasin vectoriel.

Fournit des méthodes pour interagir avec l'API OpenAI pour gérer les magasins vectoriels.

Représente un client pour interagir avec l'API OpenAI, étendant les fonctionnalités de base du client AI.

Fournit des méthodes pour interagir avec l'API OpenAI pour gérer les étapes d'exécution au sein des threads.

Fournit des méthodes pour interagir avec l'API OpenAI pour gérer les fichiers.

Fournit des méthodes pour interagir avec l'API OpenAI pour gérer les messages de thread.

Fournit des méthodes pour interagir avec l'API OpenAI pour gérer les threads.

Fournit des méthodes pour interagir avec l'API OpenAI pour gérer les assistants.

Fournit une méthode pour interagir avec l'API OpenAI pour créer des complétions.

Fournit des méthodes pour interagir avec l'API OpenAI pour gérer les exécutions au sein des threads.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Obtient ou définit le délai de retour en secondes. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Obtient ou définit le nombre maximum de tentatives de requêtes HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Obtient ou définit l'intervalle de sondage en secondes. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Obtient ou définit le délai d'expiration du sondage en secondes. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Annule une exécution existante au sein d'un thread de manière asynchrone. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Annule un lot de fichiers de magasin vectoriel spécifique de manière asynchrone. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Crée un nouvel assistant de manière asynchrone. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Crée une nouvelle complétion de manière asynchrone. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Crée une exécution au sein d'un thread spécifié de manière asynchrone. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Crée un thread et une exécution à l'intérieur de celui-ci de manière asynchrone. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Crée un nouveau thread de manière asynchrone. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Crée un nouveau message au sein d'un thread de manière asynchrone. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Crée un nouveau magasin vectoriel et attend qu'il soit complété de manière asynchrone. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Crée un nouveau magasin vectoriel de manière asynchrone. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Crée un nouveau fichier de magasin vectoriel de manière asynchrone. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Crée un nouveau lot de fichiers de magasin vectoriel de manière asynchrone. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Supprime un assistant existant de manière asynchrone. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Supprime un fichier spécifique de manière asynchrone. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Supprime un thread existant de manière asynchrone. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Supprime un message au sein d'un thread de manière asynchrone. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Supprime un magasin vectoriel de manière asynchrone. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string) | Supprime un fichier au sein d'un magasin vectoriel de manière asynchrone. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Dispose des ressources utilisées par le [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Récupère les détails d'un assistant spécifique de manière asynchrone. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Récupère une liste d'assistants de manière asynchrone. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Obtient une instance de [`IChatCopilot`](../ichatcopilot/) avec les options spécifiées. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Récupère les détails d'un fichier spécifique de manière asynchrone. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Récupère une liste de fichiers de manière asynchrone en fonction de l'objectif spécifié. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Obtient une instance de [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) avec les options spécifiées. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Récupère les détails d'une exécution spécifique au sein d'un thread de manière asynchrone. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Récupère une liste d'exécutions pour un thread spécifié de manière asynchrone. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Récupère les détails d'une étape spécifique au sein d'une exécution de manière asynchrone. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Récupère une liste d'étapes pour une exécution spécifique au sein d'un thread de manière asynchrone. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Obtient une instance de [`ISummaryCopilot`](../isummarycopilot/) avec les options spécifiées. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Récupère les détails d'un thread spécifique de manière asynchrone. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Récupère les détails d'un message spécifique au sein d'un thread de manière asynchrone. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Récupère une liste de messages pour un thread spécifique de manière asynchrone. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Récupère les détails d'un magasin vectoriel spécifique de manière asynchrone. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string) | Récupère les détails d'un fichier spécifique au sein d'un magasin vectoriel de manière asynchrone. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Récupère les détails d'un lot de fichiers de magasin vectoriel spécifique de manière asynchrone. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Récupère une liste de fichiers au sein d'un lot de fichiers de magasin vectoriel spécifique de manière asynchrone. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Récupère une liste de fichiers au sein d'un magasin vectoriel spécifique de manière asynchrone. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Récupère une liste de magasins vectoriels de manière asynchrone. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifie un assistant existant de manière asynchrone. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifie une exécution existante au sein d'un thread de manière asynchrone. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest) | Modifie un thread existant de manière asynchrone. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest) | Modifie un message existant au sein d'un thread de manière asynchrone. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifie un magasin vectoriel existant de manière asynchrone. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Exécute l'assistant avec le threadId spécifié et le runCreateRequest, et obtient de manière asynchrone la réponse de l'assistant. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Télécharge un fichier de manière asynchrone sur le serveur OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Attend le premier message de l'assistant au sein d'un thread de manière asynchrone. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Attend qu'une exécution soit complétée au sein d'un thread de manière asynchrone. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Attend qu'un message de thread spécifique soit complété de manière asynchrone. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Attend qu'un fichier de magasin vectoriel spécifique soit complété de manière asynchrone. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Attend qu'un magasin vectoriel spécifique soit complété de manière asynchrone. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Crée une nouvelle instance de [`Builder`](../openaiclient.builder/) avec la clé API fournie. |

## Autres Membres

| Nom | Description |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Classe Builder pour créer une instance de `OpenAIClient`. |

### Voir Aussi

* class [AIClientBase](../aiclientbase/)
* interface [IChatClient&lt;TOptions&gt;](../ichatclient-1/)
* class [OpenAIChatCopilotOptions](../openaichatcopilotoptions/)
* interface [IImageDescriptionClient&lt;TOptions&gt;](../iimagedescriptionclient-1/)
* class [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions/)
* interface [IOpenAIClient](../iopenaiclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)