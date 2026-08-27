---
title: "IOpenAIClient.RunAndGetAssistantResponseAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Exécute l'assistant avec le threadId spécifié et runCreateRequest et récupère de façon asynchrone la réponse de l'assistant"
type: docs
weight: 410
url: /fr/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## IOpenAIClient.RunAndGetAssistantResponseAsync method

Exécute l'assistant avec le threadId spécifié et runCreateRequest, et récupère de manière asynchrone la réponse de l'assistant.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil. |
| runCreateRequest | RunCreateRequest | La requête de création d'exécution. |
| cancellationToken | Nullable`1 | Le jeton d'annulation (facultatif). |

### Valeur de retour

Une tâche représentant l'opération asynchrone avec la chaîne de réponse de l'assistant.

### Voir aussi

* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


