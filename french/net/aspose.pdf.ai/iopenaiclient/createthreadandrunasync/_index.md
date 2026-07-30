---
title: "IOpenAIClient.CreateThreadAndRunAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Crée un fil et une exécution à l'intérieur de celui-ci de manière asynchrone"
type: docs
weight: 60
url: /fr/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## IOpenAIClient.CreateThreadAndRunAsync method

Crée un fil et une exécution à l'intérieur de celui-ci de façon asynchrone.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | Les détails de la requête pour créer le fil et l'exécution. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création du fil et de l'exécution.

### Voir aussi

* class [RunResponse](../../runresponse/)
* class [RunThreadCreateRequest](../../runthreadcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


