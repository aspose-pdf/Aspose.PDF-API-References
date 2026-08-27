---
title: "OpenAIClient.DeleteThreadAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode OpenAIClient. Supprime un fil existant de manière asynchrone"
type: docs
weight: 150
url: /fr/net/aspose.pdf.ai/openaiclient/deletethreadasync/
---
## OpenAIClient.DeleteThreadAsync method

Supprime un fil existant de façon asynchrone.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil à supprimer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut de l'opération de suppression.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du fil est nul ou vide. |

### Voir aussi

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


