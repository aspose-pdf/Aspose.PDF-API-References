---
title: IOpenAIClient.DeleteVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Supprime un fichier dans un magasin de vecteurs de manière asynchrone
type: docs
weight: 180
url: /fr/net/aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/
---
## Méthode IOpenAIClient.DeleteVectorStoreFileAsync

Supprime un fichier dans un magasin de vecteurs de manière asynchrone.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs contenant le fichier à supprimer. |
| fileId | String | L'ID du fichier à supprimer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut de l'opération de suppression.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du magasin de vecteurs est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fichier est nul ou vide. |

### Voir aussi

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)