---
title: IOpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Attend le premier message de l'assistant dans un fil de discussion de manière asynchrone
type: docs
weight: 430
url: /fr/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/
---
## Méthode IOpenAIClient.WaitForAssistantMessageAsync

Attend le premier message de l'assistant dans un fil de discussion de manière asynchrone.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil à surveiller pour le premier message de l'assistant. |
| queryParameters | ThreadMessageListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des messages. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le premier message de l'assistant dans le fil.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fil est nul ou vide. |

### Voir aussi

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)