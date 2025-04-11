---
title: OpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Modifie un message existant dans un fil de discussion de manière asynchrone
type: docs
weight: 420
url: /fr/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## Méthode OpenAIClient.ModifyThreadMessageAsync

Modifie un message existant dans un fil de discussion de manière asynchrone.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil de discussion contenant le message à modifier. |
| threadMessageId | String | L'ID du message à modifier. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Les détails de la demande pour modifier le message. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la modification du message.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fil de discussion est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du message du fil de discussion est nul ou vide. |

### Voir aussi

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)