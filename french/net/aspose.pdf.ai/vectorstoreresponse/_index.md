---
title: "Classe VectorStoreResponse"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.VectorStoreResponse. L'objet du magasin de vecteurs"
type: docs
weight: 1480
url: /fr/net/aspose.pdf.ai/vectorstoreresponse/
---
## VectorStoreResponse class

L'objet du magasin de vecteurs.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où le magasin de vecteurs a été créé. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Obtient ou définit la politique d'expiration d'un magasin vectoriel. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où le magasin de vecteurs expirera. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | Obtient ou définit le nombre de fichiers qui ont été traités. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | Obtient ou définit l'identifiant, qui peut être référencé dans les points de terminaison API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a réussi. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où le magasin de vecteurs a été actif pour la dernière fois. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur pouvant être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent contenir au maximum 64 caractères et les valeurs au maximum 512 caractères. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Obtient ou définit le nom du magasin vectoriel. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours vector_store. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison d'erreur. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Obtient ou définit le statut du magasin de vecteurs, qui peut être soit expired, in_progress, ou completed. Un statut completed indique que le magasin de vecteurs est prêt à être utilisé. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Obtient ou définit le nombre total d'octets utilisés par les fichiers du magasin de vecteurs. |

### Voir aussi

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


