---
title: OpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Attend qu'un fichier de magasin de vecteurs spécifique soit complété de manière asynchrone
type: docs
weight: 490
url: /fr/net/aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/
---
## Méthode OpenAIClient.WaitForVectorStoreFileToCompleteAsync

Attend qu'un fichier de magasin de vecteurs spécifique soit complété de manière asynchrone.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs contenant le fichier. |
| fileId | String | L'ID du fichier à surveiller jusqu'à son achèvement. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut final du fichier.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du magasin de vecteurs est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fichier est nul ou vide. |

### Voir aussi

* classe [VectorStoreFileResponse](../../vectorstorefileresponse/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)