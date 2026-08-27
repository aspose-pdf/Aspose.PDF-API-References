---
title: "IOpenAIClient.ModifyVectorStoreAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "IOpenAIClient méthode. Modifie un magasin de vecteurs existant de manière asynchrone"
type: docs
weight: 400
url: /fr/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## IOpenAIClient.ModifyVectorStoreAsync method

Modifie un magasin de vecteurs existant de manière asynchrone.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs à modifier. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | L'objet de requête contenant les détails de la modification. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la modification du magasin de vecteurs.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


