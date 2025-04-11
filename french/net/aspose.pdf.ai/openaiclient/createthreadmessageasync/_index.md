---
title: OpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Crée un nouveau message dans un fil de discussion de manière asynchrone
type: docs
weight: 80
url: /fr/net/aspose.pdf.ai/openaiclient/createthreadmessageasync/
---
## Méthode OpenAIClient.CreateThreadMessageAsync

Crée un nouveau message dans un fil de discussion de manière asynchrone.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil de discussion où le message sera créé. |
| threadMessageRequest | ThreadMessageCreateRequest | Les détails de la demande pour créer le message. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création du message.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fil est nul ou vide. |

### Voir aussi

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)