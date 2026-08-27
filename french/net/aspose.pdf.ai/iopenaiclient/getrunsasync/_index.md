---
title: "IOpenAIClient.GetRunsAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "IOpenAIClient méthode. Récupère une liste d'exécutions pour un fil spécifié de manière asynchrone"
type: docs
weight: 240
url: /fr/net/aspose.pdf.ai/iopenaiclient/getrunsasync/
---
## IOpenAIClient.GetRunsAsync method

Récupère une liste d'exécutions pour un fil spécifié de façon asynchrone.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil dont il faut récupérer les exécutions. |
| queryParameters | RunListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des exécutions. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient une liste d'exécutions.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du fil est nul ou vide. |

### Voir aussi

* class [RunListResponse](../../runlistresponse/)
* class [RunListQueryParameters](../../runlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


