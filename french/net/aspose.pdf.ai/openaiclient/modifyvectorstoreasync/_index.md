---
title: OpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Modifie un magasin de vecteurs existant de manière asynchrone
type: docs
weight: 430
url: /fr/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## Méthode OpenAIClient.ModifyVectorStoreAsync

Modifie un magasin de vecteurs existant de manière asynchrone.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs à modifier. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | L'objet de demande contenant les détails de la modification. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la modification du magasin de vecteurs.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)