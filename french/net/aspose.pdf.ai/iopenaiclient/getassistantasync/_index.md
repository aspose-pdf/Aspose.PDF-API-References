---
title: IOpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Récupère les détails d'un assistant spécifique de manière asynchrone
type: docs
weight: 190
url: /fr/net/aspose.pdf.ai/iopenaiclient/getassistantasync/
---
## Méthode IOpenAIClient.GetAssistantAsync

Récupère les détails d'un assistant spécifique de manière asynchrone.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| assistantId | String | L'ID de l'assistant à récupérer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient les détails de l'assistant.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID de l'assistant est nul ou vide. |

### Voir aussi

* classe [AssistantResponse](../../assistantresponse/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)