---
title: "IOpenAIClient.DeleteFileAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "IOpenAIClient méthode. Supprime un fichier spécifique de manière asynchrone"
type: docs
weight: 140
url: /fr/net/aspose.pdf.ai/iopenaiclient/deletefileasync/
---
## IOpenAIClient.DeleteFileAsync method

Supprime un fichier spécifique de façon asynchrone.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileId | String | L'ID du fichier à supprimer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut de l'opération de suppression.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fichier est nul ou vide. |

### Voir aussi

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


