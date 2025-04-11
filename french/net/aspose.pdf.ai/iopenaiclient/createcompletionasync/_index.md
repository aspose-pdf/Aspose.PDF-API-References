---
title: IOpenAIClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Crée une nouvelle complétion de manière asynchrone
type: docs
weight: 40
url: /fr/net/aspose.pdf.ai/iopenaiclient/createcompletionasync/
---
## Méthode IOpenAIClient.CreateCompletionAsync

Crée une nouvelle complétion de manière asynchrone.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | L'objet de demande contenant les détails pour créer la complétion. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création de la complétion.

### Voir aussi

* classe [CompletionResponse](../../completionresponse/)
* classe [CompletionCreateRequest](../../completioncreaterequest/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)