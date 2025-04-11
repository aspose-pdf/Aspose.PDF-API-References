---
title: IOpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Supprime un message dans un fil de discussion de manière asynchrone
type: docs
weight: 160
url: /fr/net/aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/
---
## Méthode IOpenAIClient.DeleteThreadMessageAsync

Supprime un message dans un fil de discussion de manière asynchrone.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil contenant le message à supprimer. |
| threadMessageId | String | L'ID du message à supprimer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut de l'opération de suppression.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fil est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du message du fil est nul ou vide. |

### Voir aussi

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)