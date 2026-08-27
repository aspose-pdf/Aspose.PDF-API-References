---
title: "IOpenAIClient.GetAssistantAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Récupère les détails d'un assistant spécifique de façon asynchrone"
type: docs
weight: 190
url: /fr/net/aspose.pdf.ai/iopenaiclient/getassistantasync/
---
## IOpenAIClient.GetAssistantAsync method

Récupère les détails d'un assistant spécifique de façon asynchrone.

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
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID de l'assistant est nul ou vide. |

### Voir aussi

* class [AssistantResponse](../../assistantresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


