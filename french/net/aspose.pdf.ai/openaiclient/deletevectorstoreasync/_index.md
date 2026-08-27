---
title: "OpenAIClient.DeleteVectorStoreAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "méthode OpenAIClient. Supprime un magasin de vecteurs de manière asynchrone"
type: docs
weight: 170
url: /fr/net/aspose.pdf.ai/openaiclient/deletevectorstoreasync/
---
## OpenAIClient.DeleteVectorStoreAsync method

Supprime un magasin de vecteurs de façon asynchrone.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs à supprimer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut de l'opération de suppression.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


