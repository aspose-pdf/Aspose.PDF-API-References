---
title: IOpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Crée un nouveau fichier de magasin de vecteurs de manière asynchrone
type: docs
weight: 110
url: /fr/net/aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/
---
## Méthode IOpenAIClient.CreateVectorStoreFileAsync

Crée un nouveau fichier de magasin de vecteurs de manière asynchrone.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs où le fichier sera créé. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | L'objet de demande contenant les détails pour créer le fichier. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création du fichier.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* classe [VectorStoreFileResponse](../../vectorstorefileresponse/)
* classe [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)