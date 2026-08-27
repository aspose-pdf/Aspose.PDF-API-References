---
title: "IOpenAIClient.GetThreadAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Récupère les détails d'un fil spécifique de manière asynchrone"
type: docs
weight: 270
url: /fr/net/aspose.pdf.ai/iopenaiclient/getthreadasync/
---
## IOpenAIClient.GetThreadAsync method

Récupère les détails d'un fil de discussion spécifique de manière asynchrone.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil à récupérer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient les détails du fil.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du fil est nul ou vide. |

### Voir aussi

* class [ThreadResponse](../../threadresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


