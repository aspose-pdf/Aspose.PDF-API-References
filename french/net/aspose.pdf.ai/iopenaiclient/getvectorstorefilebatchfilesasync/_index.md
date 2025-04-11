---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Récupère une liste de fichiers dans un lot de fichiers de magasin vectoriel spécifique de manière asynchrone
type: docs
weight: 330
url: /fr/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## Méthode IOpenAIClient.GetVectorStoreFileBatchFilesAsync

Récupère une liste de fichiers dans un lot de fichiers de magasin vectoriel spécifique de manière asynchrone.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin vectoriel contenant le lot de fichiers. |
| fileBatchId | String | L'ID du lot de fichiers à partir duquel récupérer les fichiers. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des fichiers. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient une liste de fichiers dans le lot de fichiers.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du magasin vectoriel est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du lot de fichiers du magasin vectoriel est nul ou vide. |

### Voir aussi

* classe [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* classe [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)