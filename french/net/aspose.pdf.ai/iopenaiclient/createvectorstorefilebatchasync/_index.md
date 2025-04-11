---
title: IOpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Crée un nouveau lot de fichiers de magasin de vecteurs de manière asynchrone
type: docs
weight: 120
url: /fr/net/aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/
---
## Méthode IOpenAIClient.CreateVectorStoreFileBatchAsync

Crée un nouveau lot de fichiers de magasin de vecteurs de manière asynchrone.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs où le lot de fichiers sera créé. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | L'objet de demande contenant les détails pour créer le lot de fichiers. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création du lot de fichiers.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* classe [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* classe [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)