---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.VectorStoreResponse. L'objet de stockage vectoriel
type: docs
weight: 1390
url: /fr/net/aspose.pdf.ai/vectorstoreresponse/
---
## Classe VectorStoreResponse

L'objet de stockage vectoriel.

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
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où le stockage vectoriel a été créé. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Obtient ou définit la politique d'expiration pour un stockage vectoriel. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où le stockage vectoriel expirera. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | Obtient ou définit le nombre de fichiers qui ont été traités. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | Obtient ou définit l'identifiant, qui peut être référencé dans les points de terminaison de l'API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a été réussie. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où le stockage vectoriel a été le plus récemment actif. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur qui peuvent être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent avoir une longueur maximale de 64 caractères et les valeurs peuvent avoir une longueur maximale de 512 caractères. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Obtient ou définit le nom du stockage vectoriel. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours vector_store. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison d'erreur. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Obtient ou définit le statut du stockage vectoriel, qui peut être soit expiré, en_cours, ou terminé. Un statut de terminé indique que le stockage vectoriel est prêt à être utilisé. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Obtient ou définit le nombre total d'octets utilisés par les fichiers dans le stockage vectoriel. |

### Voir aussi

* classe [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* interface [IStatus](../istatus/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)