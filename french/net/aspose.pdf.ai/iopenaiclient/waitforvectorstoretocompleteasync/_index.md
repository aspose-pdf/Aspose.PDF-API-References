---
title: IOpenAIClient.WaitForVectorStoreToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Attend qu'un magasin de vecteurs spécifique se termine de manière asynchrone
type: docs
weight: 470
url: /fr/net/aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/
---
## Méthode IOpenAIClient.WaitForVectorStoreToCompleteAsync

Attend qu'un magasin de vecteurs spécifique se termine de manière asynchrone.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs à surveiller jusqu'à la fin. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut final du magasin de vecteurs.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)