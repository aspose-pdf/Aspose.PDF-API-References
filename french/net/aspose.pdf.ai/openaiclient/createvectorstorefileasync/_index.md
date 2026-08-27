---
title: "OpenAIClient.CreateVectorStoreFileAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "méthode OpenAIClient. Crée un nouveau fichier de magasin de vecteurs de manière asynchrone"
type: docs
weight: 110
url: /fr/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## OpenAIClient.CreateVectorStoreFileAsync method

Crée un nouveau fichier de magasin de vecteurs de façon asynchrone.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | L'ID du magasin de vecteurs où le fichier sera créé. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | L'objet de requête contenant les détails pour créer le fichier. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de la création du fichier.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du magasin de vecteurs est nul ou vide. |

### Voir aussi

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


