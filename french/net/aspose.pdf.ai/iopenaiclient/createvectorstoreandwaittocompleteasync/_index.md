---
title: "IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Crée un nouveau magasin de vecteurs et attend qu’il se termine de façon asynchrone"
type: docs
weight: 90
url: /fr/net/aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/
---
## IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync method

Crée un nouveau magasin de vecteurs et attend qu'il se termine de façon asynchrone.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | L'objet de requête contenant les détails pour créer le magasin de vecteurs. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création du magasin de vecteurs après achèvement.

### Voir aussi

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


