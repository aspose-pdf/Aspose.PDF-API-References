---
title: "IOpenAIClient.GetVectorStoreFilesAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "IOpenAIClient méthode. Récupère une liste de fichiers dans un magasin de vecteurs spécifique de manière asynchrone"
type: docs
weight: 340
url: /fr/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/
---
## IOpenAIClient.GetVectorStoreFilesAsync method

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
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


