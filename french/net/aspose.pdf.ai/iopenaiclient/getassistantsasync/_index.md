---
title: IOpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Récupère une liste d'assistants de manière asynchrone
type: docs
weight: 200
url: /fr/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## Méthode IOpenAIClient.GetAssistantsAsync

Récupère une liste d'assistants de manière asynchrone.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des assistants. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la liste des assistants.

### Voir aussi

* classe [AssistantListResponse](../../assistantlistresponse/)
* classe [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)