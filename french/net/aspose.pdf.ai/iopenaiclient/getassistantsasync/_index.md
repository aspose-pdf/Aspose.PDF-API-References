---
title: "IOpenAIClient.GetAssistantsAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "méthode IOpenAIClient. Récupère une liste d'assistants de façon asynchrone"
type: docs
weight: 200
url: /fr/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## IOpenAIClient.GetAssistantsAsync method

Récupère une liste d'assistants de façon asynchrone.

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

* class [AssistantListResponse](../../assistantlistresponse/)
* class [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


