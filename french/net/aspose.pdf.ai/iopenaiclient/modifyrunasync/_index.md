---
title: IOpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Modifie une exécution existante dans un fil de manière asynchrone
type: docs
weight: 370
url: /fr/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/
---
## Méthode IOpenAIClient.ModifyRunAsync

Modifie une exécution existante dans un fil de manière asynchrone.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil contenant l'exécution. |
| runId | String | L'ID de l'exécution à modifier. |
| assistantModifyRequest | RunModifyRequest | Les détails de la demande pour modifier l'exécution. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la modification de l'exécution.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fil est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID de l'exécution est nul ou vide. |

### Voir aussi

* classe [RunResponse](../../runresponse/)
* classe [RunModifyRequest](../../runmodifyrequest/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)