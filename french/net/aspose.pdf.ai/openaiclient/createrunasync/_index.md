---
title: OpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Crée une exécution dans un fil spécifié de manière asynchrone
type: docs
weight: 50
url: /fr/net/aspose.pdf.ai/openaiclient/createrunasync/
---
## Méthode OpenAIClient.CreateRunAsync

Crée une exécution dans un fil spécifié de manière asynchrone.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil où l'exécution sera créée. |
| runCreateRequest | RunCreateRequest | Les détails de la demande pour créer l'exécution. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création de l'exécution.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fil est nul ou vide. |

### Voir aussi

* classe [RunResponse](../../runresponse/)
* classe [RunCreateRequest](../../runcreaterequest/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)