---
title: "IOpenAIClient.GetVectorStoreAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Récupère les détails d'un magasin de vecteurs spécifique de manière asynchrone"
type: docs
weight: 300
url: /fr/net/aspose.pdf.ai/iopenaiclient/getvectorstoreasync/
---
## IOpenAIClient.GetVectorStoreAsync method

Récupère les détails d'un magasin de vecteurs spécifique de manière asynchrone.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs à récupérer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient les détails du magasin de vecteurs.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* class [VectorStoreResponse](../../vectorstoreresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


