---
title: IOpenAIClient.GetThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Récupère les détails d'un message spécifique dans un fil de discussion de manière asynchrone
type: docs
weight: 280
url: /fr/net/aspose.pdf.ai/iopenaiclient/getthreadmessageasync/
---
## Méthode IOpenAIClient.GetThreadMessageAsync

Récupère les détails d'un message spécifique dans un fil de discussion de manière asynchrone.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil contenant le message. |
| threadMessageId | String | L'ID du message à récupérer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient les détails du message du fil.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fil est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du message du fil est nul ou vide. |

### Voir aussi

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)