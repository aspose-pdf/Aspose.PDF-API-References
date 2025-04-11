---
title: IOpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Récupère une liste de magasins de vecteurs de manière asynchrone
type: docs
weight: 350
url: /fr/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## Méthode IOpenAIClient.GetVectorStoresAsync

Récupère une liste de magasins de vecteurs de manière asynchrone.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Paramètres de requête optionnels pour filtrer la liste des magasins de vecteurs. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient une liste de magasins de vecteurs.

### Voir aussi

* classe [VectorStoreListResponse](../../vectorstorelistresponse/)
* classe [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)