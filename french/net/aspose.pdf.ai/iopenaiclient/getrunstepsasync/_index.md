---
title: IOpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Récupère une liste d'étapes pour un exécution spécifique dans un fil de manière asynchrone
type: docs
weight: 260
url: /fr/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## Méthode IOpenAIClient.GetRunStepsAsync

Récupère une liste d'étapes pour une exécution spécifique dans un fil de manière asynchrone.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil contenant l'exécution. |
| runId | String | L'ID de l'exécution à partir de laquelle récupérer les étapes. |
| queryParameters | RunStepListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des étapes d'exécution. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la liste des étapes d'exécution.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fil est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID de l'exécution est nul ou vide. |

### Voir aussi

* classe [RunStepListResponse](../../runsteplistresponse/)
* classe [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)