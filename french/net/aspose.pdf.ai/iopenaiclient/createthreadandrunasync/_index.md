---
title: IOpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Crée un thread et un run à l'intérieur de celui-ci de manière asynchrone
type: docs
weight: 60
url: /fr/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## Méthode IOpenAIClient.CreateThreadAndRunAsync

Crée un thread et un run à l'intérieur de celui-ci de manière asynchrone.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | Les détails de la demande pour créer le thread et le run. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création du thread et du run.

### Voir aussi

* classe [RunResponse](../../runresponse/)
* classe [RunThreadCreateRequest](../../runthreadcreaterequest/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)