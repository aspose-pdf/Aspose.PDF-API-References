---
title: OpenAIClient.DeleteFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Supprime un fichier spécifique de manière asynchrone
type: docs
weight: 140
url: /fr/net/aspose.pdf.ai/openaiclient/deletefileasync/
---
## Méthode OpenAIClient.DeleteFileAsync

Supprime un fichier spécifique de manière asynchrone.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileId | String | L'ID du fichier à supprimer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient l'état de l'opération de suppression.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fichier est nul ou vide. |

### Voir aussi

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)