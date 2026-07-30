---
title: "IOpenAIClient.UploadFileAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Téléverse un fichier de façon asynchrone vers le serveur OpenAI"
type: docs
weight: 420
url: /fr/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync method

Téléverse un fichier de manière asynchrone vers le serveur OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| purpose | String | Le but du téléversement du fichier, décrivant généralement comment le fichier sera utilisé. |
| fileName | String | Le nom du fichier à téléverser. |
| fileBytes | Byte[] | Le tableau d'octets contenant les données du fichier. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse du téléversement du fichier.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque le but du fichier est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancée lorsque le nom du fichier est nul ou vide. |

### Voir aussi

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


