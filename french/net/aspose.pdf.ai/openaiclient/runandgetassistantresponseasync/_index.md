---
title: OpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Exécute l'assistant avec le threadId spécifié et runCreateRequest et obtient de manière asynchrone la réponse de l'assistant
type: docs
weight: 440
url: /fr/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## Méthode OpenAIClient.RunAndGetAssistantResponseAsync

Exécute l'assistant avec le threadId spécifié et runCreateRequest, et obtient de manière asynchrone la réponse de l'assistant.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du thread. |
| runCreateRequest | RunCreateRequest | La demande de création d'exécution. |
| cancellationToken | Nullable`1 | Le jeton d'annulation (facultatif). |

### Valeur de retour

Une tâche représentant l'opération asynchrone avec la chaîne de réponse de l'assistant.

### Voir aussi

* classe [RunCreateRequest](../../runcreaterequest/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)