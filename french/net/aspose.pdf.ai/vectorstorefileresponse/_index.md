---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.VectorStoreFileResponse. Une réponse de fichier de magasin vectoriel
type: docs
weight: 1350
url: /fr/net/aspose.pdf.ai/vectorstorefileresponse/
---
## Classe VectorStoreFileResponse

Une réponse de fichier de magasin vectoriel.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où le fichier de magasin vectoriel a été créé. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Obtient ou définit l'identifiant, qui peut être référencé dans les points de terminaison de l'API. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a été réussie. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Obtient ou définit la dernière erreur associée à ce fichier de magasin vectoriel. Sera nul s'il n'y a pas d'erreurs. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison de l'erreur. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Obtient ou définit le statut du fichier de magasin vectoriel, qui peut être soit en_cours, terminé, annulé ou échoué. Le statut terminé indique que le fichier de magasin vectoriel est prêt à être utilisé. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Obtient ou définit l'utilisation totale du magasin vectoriel en octets. Notez que cela peut être différent de la taille du fichier d'origine. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Obtient ou définit l'ID du magasin vectoriel auquel le fichier est attaché. |

### Voir aussi

* classe [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)