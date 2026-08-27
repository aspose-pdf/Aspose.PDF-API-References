---
title: "Classe VectorStoreFileResponse"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.AI.VectorStoreFileResponse classe. Une réponse de fichier du magasin de vecteurs."
type: docs
weight: 1440
url: /fr/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse class

Une réponse de fichier de magasin de vecteurs.

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
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Obtient ou définit l’horodatage Unix (en secondes) du moment où le fichier du magasin de vecteurs a été créé. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Obtient ou définit l’identifiant, qui peut être référencé dans les points de terminaison API. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a réussi. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Obtient ou définit la dernière erreur associée à ce fichier du magasin de vecteurs. Sera null s’il n’y a aucune erreur. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Obtient ou définit le type d’objet, qui est toujours vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison d'erreur. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Obtient ou définit le statut du fichier du magasin de vecteurs, qui peut être in_progress, completed, cancelled ou failed. Le statut completed indique que le fichier du magasin de vecteurs est prêt à être utilisé. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Obtient ou définit l’utilisation totale du magasin de vecteurs en octets. Notez que cela peut différer de la taille du fichier original. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Obtient ou définit l'ID du magasin de vecteurs auquel le File est attaché. |

### Voir aussi

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


