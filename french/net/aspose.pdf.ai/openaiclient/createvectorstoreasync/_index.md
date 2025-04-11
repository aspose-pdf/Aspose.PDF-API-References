---
title: OpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Crée un nouveau magasin de vecteurs de manière asynchrone
type: docs
weight: 100
url: /fr/net/aspose.pdf.ai/openaiclient/createvectorstoreasync/
---
## Méthode OpenAIClient.CreateVectorStoreAsync

Crée un nouveau magasin de vecteurs de manière asynchrone.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | L'objet de demande contenant les détails pour créer le magasin de vecteurs. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création du magasin de vecteurs.

### Voir aussi

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)