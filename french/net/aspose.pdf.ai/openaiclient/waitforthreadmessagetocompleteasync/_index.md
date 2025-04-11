---
title: OpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Attend qu'un message de thread spécifique soit complété de manière asynchrone
type: docs
weight: 480
url: /fr/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/
---
## Méthode OpenAIClient.WaitForThreadMessageToCompleteAsync

Attend qu'un message de thread spécifique soit complété de manière asynchrone.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du thread contenant le message. |
| threadMessageId | String | L'ID du message à surveiller jusqu'à son achèvement. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut final du message.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du thread est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du message de thread est nul ou vide. |

### Voir aussi

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)