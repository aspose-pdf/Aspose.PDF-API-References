---
title: "Classe OpenAIClient"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.OpenAIClient. Fournit des méthodes pour interagir avec l'API OpenAI afin de gérer les lots de fichiers de magasin vectoriel."
type: docs
weight: 900
url: /fr/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient class

Fournit des méthodes pour interagir avec l'API OpenAI afin de gérer les lots de fichiers du magasin de vecteurs.

Fournit des méthodes pour interagir avec l'API OpenAI afin de gérer les fichiers de magasin vectoriel.

Fournit des méthodes pour interagir avec l'API OpenAI afin de gérer les magasins vectoriels.

Représente un client pour interagir avec l'API OpenAI, en étendant les fonctionnalités de base du client IA.

Fournit des méthodes pour interagir avec l'API OpenAI afin de gérer les étapes d'exécution au sein des fils.

Fournit des méthodes pour interagir avec l'API OpenAI afin de gérer les fichiers.

Fournit des méthodes pour interagir avec l'API OpenAI afin de gérer les messages de fil.

Fournit des méthodes pour interagir avec l'API OpenAI afin de gérer les fils.

Fournit des méthodes pour interagir avec l'API OpenAI afin de gérer les assistants.

Fournit une méthode pour interagir avec l'API OpenAI afin de créer des complétions.

Fournit des méthodes pour interagir avec l'API OpenAI afin de gérer les exécutions au sein des fils.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, 
    IOcrClient<OpenAIOcrCopilotOptions>, IOpenAIClient, ISummaryClient<OpenAISummaryCopilotOptions>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Obtient ou définit le délai de backoff en secondes. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Obtient ou définit le nombre maximal de nouvelles tentatives de requêtes HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Obtient ou définit l'intervalle d'interrogation en secondes. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Obtient ou définit le délai d'expiration de l'interrogation en secondes. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Annule de manière asynchrone une exécution existante au sein d'un fil. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Annule de manière asynchrone un lot de fichiers de magasin vectoriel spécifique. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Crée de manière asynchrone un nouvel assistant. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Crée une nouvelle complétion de façon asynchrone. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Crée une exécution dans un fil spécifié de façon asynchrone. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Crée un fil et une exécution à l'intérieur de celui-ci de façon asynchrone. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Crée un nouveau fil de façon asynchrone. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Crée un nouveau message dans un fil de façon asynchrone. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Crée un nouveau magasin de vecteurs et attend qu'il se termine de façon asynchrone. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Crée un nouveau magasin de vecteurs de façon asynchrone. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Crée un nouveau fichier de magasin de vecteurs de façon asynchrone. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Crée un nouveau lot de fichiers de magasin de vecteurs de façon asynchrone. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Supprime un assistant existant de façon asynchrone. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Supprime un fichier spécifique de façon asynchrone. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Supprime un fil existant de façon asynchrone. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Supprime un message dans un fil de façon asynchrone. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Supprime un magasin de vecteurs de façon asynchrone. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Supprime un fichier dans un magasin de vecteurs de façon asynchrone. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Libère les ressources utilisées par le [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Récupère les détails d'un assistant spécifique de façon asynchrone. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Récupère une liste d'assistants de façon asynchrone. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Obtient une instance de [`IChatCopilot`](../ichatcopilot/) avec les options spécifiées. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Récupère les détails d'un fichier spécifique de façon asynchrone. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Récupère une liste de fichiers de façon asynchrone en fonction du but spécifié. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Obtient une instance de [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) avec les options spécifiées. |
| [GetOcrCopilot](../../aspose.pdf.ai/openaiclient/getocrcopilot/)(IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Obtient une instance de [`IOcrCopilot`](../iocrcopilot/) avec les options spécifiées. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Récupère les détails d'une exécution spécifique dans un fil de façon asynchrone. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Récupère une liste d'exécutions pour un fil spécifié de façon asynchrone. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Récupère les détails d'une étape spécifique d'une exécution de manière asynchrone. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Récupère une liste d'étapes pour une exécution spécifique dans un fil de discussion de manière asynchrone. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Obtient une instance de [`ISummaryCopilot`](../isummarycopilot/) avec les options spécifiées. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Récupère les détails d'un fil de discussion spécifique de manière asynchrone. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Récupère les détails d'un message spécifique dans un fil de discussion de manière asynchrone. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Récupère une liste de messages pour un fil de discussion spécifique de manière asynchrone. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Récupère les détails d'un magasin de vecteurs spécifique de manière asynchrone. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Récupère les détails d'un fichier spécifique dans un magasin de vecteurs de manière asynchrone. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Récupère les détails d'un lot de fichiers de magasin de vecteurs spécifique de manière asynchrone. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Récupère une liste de fichiers dans un lot de fichiers de magasin de vecteurs spécifique de manière asynchrone. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Récupère une liste de fichiers dans un magasin de vecteurs spécifique de manière asynchrone. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Récupère une liste de magasins de vecteurs de manière asynchrone. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifie un assistant existant de manière asynchrone. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifie une exécution existante dans un fil de discussion de manière asynchrone. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifie un fil de discussion existant de manière asynchrone. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifie un message existant dans un fil de discussion de manière asynchrone. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifie un magasin de vecteurs existant de manière asynchrone. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Exécute l'assistant avec le threadId spécifié et runCreateRequest, et récupère de manière asynchrone la réponse de l'assistant. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Téléverse un fichier de manière asynchrone vers le serveur OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Attend le premier message de l'assistant dans un fil de discussion de manière asynchrone. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Attend qu'une exécution se termine dans un fil de discussion de manière asynchrone. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | Attend qu'un message de fil de discussion spécifique se termine de manière asynchrone. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | Attend qu'un fichier de magasin de vecteurs spécifique se termine de manière asynchrone. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Attend qu'un magasin de vecteurs spécifique se termine de manière asynchrone. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Crée une nouvelle instance de [`Builder`](../openaiclient.builder/) avec la clé API fournie. |

## Autres membres

| Nom | Description |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Classe de constructeur pour créer une instance de `OpenAIClient`. |

### Voir aussi

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


