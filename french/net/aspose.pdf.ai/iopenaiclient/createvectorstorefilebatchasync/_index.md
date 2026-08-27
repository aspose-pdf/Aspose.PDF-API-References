---
title: "IOpenAIClient.CreateVectorStoreFileBatchAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "méthode IOpenAIClient. Crée un nouveau lot de fichiers de magasin de vecteurs de façon asynchrone"
type: docs
weight: 120
url: /fr/net/aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/
---
## IOpenAIClient.CreateVectorStoreFileBatchAsync method

Crée un nouveau lot de fichiers de magasin de vecteurs de façon asynchrone.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs où le lot de fichiers sera créé. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | L'objet de requête contenant les détails pour créer le lot de fichiers. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création du lot de fichiers.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


