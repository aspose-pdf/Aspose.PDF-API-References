---
title: "OpenAIClient.DeleteVectorStoreFileAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode OpenAIClient. Supprime un fichier dans un vector store de manière asynchrone"
type: docs
weight: 180
url: /fr/net/aspose.pdf.ai/openaiclient/deletevectorstorefileasync/
---
## OpenAIClient.DeleteVectorStoreFileAsync method

Supprime un fichier dans un magasin de vecteurs de façon asynchrone.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du vector store contenant le fichier à supprimer. |
| fileId | String | L'ID du fichier à supprimer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient le statut de l'opération de suppression.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du magasin de vecteurs est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fichier est nul ou vide. |

### Voir aussi

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


