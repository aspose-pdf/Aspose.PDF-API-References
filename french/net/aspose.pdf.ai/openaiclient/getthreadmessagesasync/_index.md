---
title: OpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Récupère une liste de messages pour un fil spécifique de manière asynchrone
type: docs
weight: 320
url: /fr/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/
---
## Méthode OpenAIClient.GetThreadMessagesAsync

Récupère une liste de messages pour un fil spécifique de manière asynchrone.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil à partir duquel récupérer les messages. |
| queryParameters | ThreadMessageListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des messages. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient une liste de messages de fil.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fil est nul ou vide. |

### Voir aussi

* class [ThreadMessageListResponse](../../threadmessagelistresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)