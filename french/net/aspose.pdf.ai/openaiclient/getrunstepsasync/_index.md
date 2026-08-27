---
title: "OpenAIClient.GetRunStepsAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode OpenAIClient. Récupère une liste d'étapes pour une exécution spécifique au sein d'un fil de discussion de manière asynchrone"
type: docs
weight: 290
url: /fr/net/aspose.pdf.ai/openaiclient/getrunstepsasync/
---
## OpenAIClient.GetRunStepsAsync method

Récupère une liste d'étapes pour une exécution spécifique dans un fil de discussion de manière asynchrone.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil contenant l'exécution. |
| runId | String | L'ID de l'exécution dont il faut récupérer les étapes. |
| queryParameters | RunStepListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des étapes d'exécution. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la liste des étapes d'exécution.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du fil est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID de l'exécution est nul ou vide. |

### Voir aussi

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


