---
title: OpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Télécharge un fichier de manière asynchrone sur le serveur OpenAI
type: docs
weight: 450
url: /fr/net/aspose.pdf.ai/openaiclient/uploadfileasync/
---
## Méthode OpenAIClient.UploadFileAsync

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

* class [FileResponse](../../fileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)