---
title: "IOpenAIClient.GetRunStepAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Récupère les détails d'une étape spécifique au sein d'une exécution de manière asynchrone"
type: docs
weight: 250
url: /fr/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## IOpenAIClient.GetRunStepAsync method

Récupère les détails d'une étape spécifique d'une exécution de manière asynchrone.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil contenant l'exécution. |
| runId | String | L'ID de l'exécution contenant l'étape. |
| runStepId | String | L'ID de l'étape d'exécution à récupérer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient les détails de l'étape d'exécution.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du fil est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID de l'exécution est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID de l'étape d'exécution est nul ou vide. |

### Voir aussi

* class [RunStepResponse](../../runstepresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


