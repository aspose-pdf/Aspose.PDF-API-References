---
title: IOpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Récupère une liste de fichiers dans un magasin de vecteurs spécifique de manière asynchrone
type: docs
weight: 340
url: /fr/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/
---
## Méthode IOpenAIClient.GetVectorStoreFilesAsync

Récupère une liste de fichiers dans un magasin de vecteurs spécifique de manière asynchrone.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs contenant les fichiers. |
| queryParameters | VectorStoreFileListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des fichiers. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient une liste de fichiers dans le magasin de vecteurs.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* classe [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* classe [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)