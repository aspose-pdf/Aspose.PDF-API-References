---
title: "IOpenAIClient.GetVectorStoreFileBatchFilesAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Récupère une liste de fichiers dans un lot de fichiers de magasin de vecteurs spécifique de manière asynchrone"
type: docs
weight: 330
url: /fr/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync method

Récupère une liste de fichiers dans un lot de fichiers de magasin de vecteurs spécifique de manière asynchrone.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs contenant le lot de fichiers. |
| fileBatchId | String | L'ID du lot de fichiers dont il faut récupérer les fichiers. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des fichiers. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient une liste de fichiers du lot de fichiers.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du magasin de vecteurs est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du lot de fichiers du magasin de vecteurs est nul ou vide. |

### Voir aussi

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


