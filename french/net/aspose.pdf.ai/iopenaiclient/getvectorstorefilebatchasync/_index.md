---
title: IOpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Récupère les détails d'un lot de fichiers de magasin de vecteurs spécifique de manière asynchrone
type: docs
weight: 320
url: /fr/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/
---
## Méthode IOpenAIClient.GetVectorStoreFileBatchAsync

Récupère les détails d'un lot de fichiers de magasin de vecteurs spécifique de manière asynchrone.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs contenant le lot de fichiers. |
| fileBatchId | String | L'ID du lot de fichiers à récupérer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient les détails du lot de fichiers.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du magasin de vecteurs est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du lot de fichiers du magasin de vecteurs est nul ou vide. |

### Voir aussi

* classe [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)