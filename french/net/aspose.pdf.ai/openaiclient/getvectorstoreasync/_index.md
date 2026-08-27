---
title: "OpenAIClient.GetVectorStoreAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode OpenAIClient. Récupère les détails d'un magasin de vecteurs spécifique de manière asynchrone"
type: docs
weight: 340
url: /fr/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## OpenAIClient.GetVectorStoreAsync method

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
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


