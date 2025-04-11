---
title: OpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Attend qu'une exécution se termine dans un thread de manière asynchrone
type: docs
weight: 470
url: /fr/net/aspose.pdf.ai/openaiclient/waitforruntocompleteasync/
---
## Méthode OpenAIClient.WaitForRunToCompleteAsync

Attend qu'une exécution se termine dans un thread de manière asynchrone.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du thread contenant l'exécution. |
| runId | String | L'ID de l'exécution à surveiller jusqu'à la fin. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut final de l'exécution.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du thread est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID de l'exécution est nul ou vide. |

### Voir aussi

* classe [RunResponse](../../runresponse/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)