---
title: "Classe ThreadMessageCreateRequest"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.AI.ThreadMessageCreateRequest classe. Représente une requête pour créer un message au sein d'un fil"
type: docs
weight: 1210
url: /fr/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest class

Représente une requête pour créer un message dans un fil.

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
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Obtient ou définit une liste de fichiers attachés au message. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Obtient ou définit le contenu du message. Peut être une chaîne ou un tableau de parties de contenu. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur pouvant être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent contenir au maximum 64 caractères et les valeurs au maximum 512 caractères. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Obtient ou définit le rôle de l'entité créant le message. Les valeurs autorisées incluent : "user", "assistant". |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Crée une nouvelle `ThreadMessageCreateRequest` avec le rôle défini sur Assistant. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Crée une nouvelle `ThreadMessageCreateRequest` avec le rôle défini sur User. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Définit les pièces jointes pour la requête de message du fil. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Ajoute un contenu de message à la requête de message du fil. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Définit le contenu du message pour la requête de message du fil. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Définit les métadonnées pour la requête de message du fil. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


