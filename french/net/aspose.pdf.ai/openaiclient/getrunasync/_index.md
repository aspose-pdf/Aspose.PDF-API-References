---
title: "OpenAIClient.GetRunAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode OpenAIClient. Récupère les détails d'une exécution spécifique au sein d'un fil de discussion de manière asynchrone"
type: docs
weight: 260
url: /fr/net/aspose.pdf.ai/openaiclient/getrunasync/
---
## OpenAIClient.GetRunAsync method

Récupère les détails d'une exécution spécifique dans un fil de façon asynchrone.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil contenant l'exécution. |
| runId | String | L'ID de l'exécution à récupérer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient les détails de l'exécution.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du fil est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID de l'exécution est nul ou vide. |

### Voir aussi

* class [RunResponse](../../runresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


