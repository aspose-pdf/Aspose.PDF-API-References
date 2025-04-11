---
title: IOpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Récupère les détails d'une étape spécifique dans un run de manière asynchrone
type: docs
weight: 250
url: /fr/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## Méthode IOpenAIClient.GetRunStepAsync

Récupère les détails d'une étape spécifique dans un run de manière asynchrone.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du thread contenant le run. |
| runId | String | L'ID du run contenant l'étape. |
| runStepId | String | L'ID de l'étape du run à récupérer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient les détails de l'étape du run.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du thread est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du run est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID de l'étape du run est nul ou vide. |

### Voir aussi

* classe [RunStepResponse](../../runstepresponse/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)