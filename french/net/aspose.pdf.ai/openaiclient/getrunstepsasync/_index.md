---
title: OpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Récupère une liste d'étapes pour un run spécifique dans un thread de manière asynchrone
type: docs
weight: 280
url: /fr/net/aspose.pdf.ai/openaiclient/getrunstepsasync/
---
## Méthode OpenAIClient.GetRunStepsAsync

Récupère une liste d'étapes pour un run spécifique dans un thread de manière asynchrone.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du thread contenant le run. |
| runId | String | L'ID du run à partir duquel récupérer les étapes. |
| queryParameters | RunStepListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des étapes du run. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la liste des étapes du run.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du thread est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du run est nul ou vide. |

### Voir aussi

* classe [RunStepListResponse](../../runsteplistresponse/)
* classe [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)