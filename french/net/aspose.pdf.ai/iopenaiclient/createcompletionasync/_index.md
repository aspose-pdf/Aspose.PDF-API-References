---
title: "IOpenAIClient.CreateCompletionAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "méthode IOpenAIClient. Crée une nouvelle complétion de façon asynchrone"
type: docs
weight: 40
url: /fr/net/aspose.pdf.ai/iopenaiclient/createcompletionasync/
---
## IOpenAIClient.CreateCompletionAsync method

Crée une nouvelle complétion de façon asynchrone.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | L'objet de requête contenant les détails pour créer la complétion. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création de la complétion.

### Voir aussi

* class [CompletionResponse](../../completionresponse/)
* class [CompletionCreateRequest](../../completioncreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


