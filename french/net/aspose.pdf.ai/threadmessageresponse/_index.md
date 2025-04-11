---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.ThreadMessageResponse. Représente un message dans un fil de discussion
type: docs
weight: 1160
url: /fr/net/aspose.pdf.ai/threadmessageresponse/
---
## Classe ThreadMessageResponse

Représente un message dans un fil de discussion.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Obtient ou définit, le cas échéant, l'ID de l'assistant qui a rédigé ce message. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Obtient ou définit une liste de fichiers joints au message. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où le message a été complété. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Obtient ou définit le contenu du message sous forme de tableau de texte et/ou d'images. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où le message a été créé. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations sur l'erreur. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Obtient ou définit l'identifiant, qui peut être référencé dans les points de terminaison de l'API. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où le message a été marqué comme incomplet. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Obtient ou définit un message incomplet, des détails sur les raisons pour lesquelles le message est incomplet. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a été réussie. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur qui peuvent être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent avoir une longueur maximale de 64 caractères et les valeurs peuvent avoir une longueur maximale de 512 caractères. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison de l'erreur. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Obtient ou définit l'entité qui a produit le message. L'un de "user" ou "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Obtient ou définit l'ID de l'exécution associée à la création de ce message. La valeur est nulle lorsque les messages sont créés manuellement. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Obtient ou définit le statut du message. L'un de queued, in_progress, requires_action ou completed. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Obtient ou définit l'ID du fil auquel ce message appartient. |

### Voir aussi

* classe [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)