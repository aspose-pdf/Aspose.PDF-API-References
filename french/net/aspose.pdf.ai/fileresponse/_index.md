---
title: Class FileResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.FileResponse. L'objet FileResponse représente un document qui a été téléchargé sur OpenAI
type: docs
weight: 400
url: /fr/net/aspose.pdf.ai/fileresponse/
---
## Classe FileResponse

L'objet FileResponse représente un document qui a été téléchargé sur OpenAI.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FileResponse](fileresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | Obtient ou définit la taille du fichier, en octets. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où le fichier a été créé. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | Obtient ou définit le nom du fichier. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | Obtient ou définit l'identifiant du fichier, qui peut être référencé dans les points de terminaison de l'API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a été réussie. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours un fichier. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | Obtient ou définit l'objectif prévu du fichier. Les valeurs prises en charge sont assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results et vision. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison d'erreur. |

### Voir aussi

* classe [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)