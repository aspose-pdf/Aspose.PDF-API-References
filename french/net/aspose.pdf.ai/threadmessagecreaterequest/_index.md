---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.ThreadMessageCreateRequest. Représente une demande de création d'un message dans un fil de discussion
type: docs
weight: 1120
url: /fr/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## Classe ThreadMessageCreateRequest

Représente une demande de création d'un message dans un fil de discussion.

```csharp
public class ThreadMessageCreateRequest
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Obtient ou définit une liste de fichiers joints au message. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Obtient ou définit le contenu du message. Peut être une chaîne ou un tableau de parties de contenu. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur qui peuvent être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent avoir une longueur maximale de 64 caractères et les valeurs peuvent avoir une longueur maximale de 512 caractères. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Obtient ou définit le rôle de l'entité créant le message. Les valeurs autorisées incluent : "user", "assistant". |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Crée une nouvelle `ThreadMessageCreateRequest` avec le rôle défini sur Assistant. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Crée une nouvelle `ThreadMessageCreateRequest` avec le rôle défini sur Utilisateur. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Définit les pièces jointes pour la demande de message dans le fil de discussion. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Ajoute un contenu de message à la demande de message dans le fil de discussion. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Définit les contenus de message pour la demande de message dans le fil de discussion. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Définit les métadonnées pour la demande de message dans le fil de discussion. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)