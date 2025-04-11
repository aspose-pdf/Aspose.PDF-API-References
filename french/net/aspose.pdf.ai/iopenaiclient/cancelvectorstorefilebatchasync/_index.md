---
title: IOpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Annule un lot de fichiers de magasin de vecteurs spécifique de manière asynchrone
type: docs
weight: 20
url: /fr/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/
---
## Méthode IOpenAIClient.CancelVectorStoreFileBatchAsync

Annule un lot de fichiers de magasin de vecteurs spécifique de manière asynchrone.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs contenant le lot de fichiers à annuler. |
| fileBatchId | String | L'ID du lot de fichiers à annuler. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse à l'annulation du lot de fichiers.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du magasin de vecteurs est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du lot de fichiers du magasin de vecteurs est nul ou vide. |

### Voir aussi

* classe [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)