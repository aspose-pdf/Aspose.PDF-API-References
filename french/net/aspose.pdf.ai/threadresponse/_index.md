---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.ThreadResponse. Représente un fil qui contient des messages
type: docs
weight: 1180
url: /fr/net/aspose.pdf.ai/threadresponse/
---
## Classe ThreadResponse

Représente un fil qui contient des messages.

```csharp
public class ThreadResponse : BaseResponse
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ThreadResponse](threadresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où le fil a été créé. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | Obtient ou définit l'identifiant, qui peut être référencé dans les points de terminaison de l'API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a été réussie. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur qui peuvent être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent avoir une longueur maximale de 64 caractères et les valeurs peuvent avoir une longueur maximale de 512 caractères. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours un fil. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison d'erreur. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Obtient ou définit un ensemble de ressources qui sont mises à disposition des outils de l'assistant dans ce fil. Les ressources sont spécifiques au type d'outil. Par exemple, l'outil code_interpreter nécessite une liste d'ID de fichiers, tandis que l'outil file_search nécessite une liste d'ID de magasin vectoriel. |

### Voir aussi

* classe [BaseResponse](../baseresponse/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)