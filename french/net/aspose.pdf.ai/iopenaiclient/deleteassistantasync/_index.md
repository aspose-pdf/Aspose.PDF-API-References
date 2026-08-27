---
title: "IOpenAIClient.DeleteAssistantAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "IOpenAIClient méthode. Supprime un assistant existant de manière asynchrone"
type: docs
weight: 130
url: /fr/net/aspose.pdf.ai/iopenaiclient/deleteassistantasync/
---
## IOpenAIClient.DeleteAssistantAsync method

Supprime un assistant existant de façon asynchrone.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| assistantId | String | L'ID de l'assistant à supprimer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut de l'opération de suppression.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID de l'assistant est nul ou vide. |

### Voir aussi

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


