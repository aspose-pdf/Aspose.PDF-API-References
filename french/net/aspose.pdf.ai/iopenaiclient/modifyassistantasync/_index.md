---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Modifie un assistant existant de manière asynchrone
type: docs
weight: 360
url: /fr/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## Méthode IOpenAIClient.ModifyAssistantAsync

Modifie un assistant existant de manière asynchrone.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| assistantId | String | L'ID de l'assistant à modifier. |
| assistantModifyRequest | AssistantModifyRequest | L'objet de demande contenant les détails de la modification. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la modification de l'assistant.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID de l'assistant est nul ou vide. |

### Voir aussi

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantModifyRequest](../../assistantmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)