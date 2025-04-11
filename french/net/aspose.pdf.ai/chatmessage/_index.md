---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.ChatMessage. Un message de complétion de chat généré par le modèle
type: docs
weight: 190
url: /fr/net/aspose.pdf.ai/chatmessage/
---
## Classe ChatMessage

Un message de complétion de chat généré par le modèle.

```csharp
public class ChatMessage
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | Initialise une nouvelle instance de la classe `ChatMessage`. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | Initialise une nouvelle instance de la classe `ChatMessage`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Obtient ou définit le contenu du message. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Obtient ou définit un nom optionnel pour le participant. Fournit des informations au modèle pour différencier les participants du même rôle. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Obtient ou définit le rôle de l'auteur des messages. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Obtient ou définit l'appel d'outil auquel ce message répond. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Obtient ou définit les appels d'outil générés par le modèle, tels que les appels de fonction. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Crée un nouvel objet ChatMessage représentant un message d'assistant. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Crée un nouvel objet ChatMessage représentant un message système. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Crée un nouvel objet ChatMessage représentant un message utilisateur. |

### Voir aussi

* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)