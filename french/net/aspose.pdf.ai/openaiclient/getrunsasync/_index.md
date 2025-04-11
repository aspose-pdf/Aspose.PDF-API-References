---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Récupère une liste d'exécutions pour un thread spécifié de manière asynchrone
type: docs
weight: 260
url: /fr/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## Méthode OpenAIClient.GetRunsAsync

Récupère une liste d'exécutions pour un thread spécifié de manière asynchrone.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du thread à partir duquel récupérer les exécutions. |
| queryParameters | RunListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des exécutions. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient une liste d'exécutions.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du thread est nul ou vide. |

### Voir aussi

* classe [RunListResponse](../../runlistresponse/)
* classe [RunListQueryParameters](../../runlistqueryparameters/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)