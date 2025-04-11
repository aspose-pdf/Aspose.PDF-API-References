---
title: IOpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Télécharge un fichier de manière asynchrone sur le serveur OpenAI
type: docs
weight: 420
url: /fr/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## Méthode IOpenAIClient.UploadFileAsync

Télécharge un fichier de manière asynchrone sur le serveur OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| purpose | String | Le but du téléchargement du fichier, décrivant généralement comment le fichier sera utilisé. |
| fileName | String | Le nom du fichier à télécharger. |
| fileBytes | Byte[] | Le tableau d'octets contenant les données du fichier. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse du téléchargement du fichier.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque le but du fichier est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancé lorsque le nom du fichier est nul ou vide. |

### Voir aussi

* classe [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)