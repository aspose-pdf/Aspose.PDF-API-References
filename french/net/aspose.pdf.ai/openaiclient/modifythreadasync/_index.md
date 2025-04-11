---
title: OpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Modifie un fil existant de manière asynchrone
type: docs
weight: 410
url: /fr/net/aspose.pdf.ai/openaiclient/modifythreadasync/
---
## Méthode OpenAIClient.ModifyThreadAsync

Modifie un fil existant de manière asynchrone.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil à modifier. |
| threadModifyRequest | ThreadModifyRequest | L'objet de demande contenant les détails de la modification. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la modification du fil.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fil est nul ou vide. |

### Voir aussi

* classe [ThreadResponse](../../threadresponse/)
* classe [ThreadModifyRequest](../../threadmodifyrequest/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)