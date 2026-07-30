---
title: "IOpenAIClient.WaitForVectorStoreToCompleteAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "IOpenAIClient méthode. Attend qu'un magasin de vecteurs spécifique se termine de manière asynchrone"
type: docs
weight: 470
url: /fr/net/aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/
---
## IOpenAIClient.WaitForVectorStoreToCompleteAsync method

Attend qu'un magasin de vecteurs spécifique se termine de manière asynchrone.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs à surveiller jusqu'à son achèvement. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient l'état final du magasin de vecteurs.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* class [VectorStoreResponse](../../vectorstoreresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


