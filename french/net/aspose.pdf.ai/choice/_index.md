---
title: "Classe Choice"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.Choice. Représente un choix dans une réponse de complétion de chat"
type: docs
weight: 210
url: /fr/net/aspose.pdf.ai/choice/
---
## Choice class

Représente un choix dans une réponse de complétion de chat.

```csharp
public class Choice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Choice](choice/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FinishReason](../../aspose.pdf.ai/choice/finishreason/) { get; set; } | Obtient ou définit la raison pour laquelle le modèle a cessé de générer des jetons. Ce sera stop si le modèle a atteint un point d'arrêt naturel ou une séquence d'arrêt fournie, length si le nombre maximal de jetons spécifié dans la requête a été atteint. |
| [Index](../../aspose.pdf.ai/choice/index/) { get; set; } | Obtient ou définit l'index du choix dans la liste des choix. |
| [Logprobs](../../aspose.pdf.ai/choice/logprobs/) { get; set; } | Obtient ou définit les informations de probabilité logarithmique pour le choix. |
| [Message](../../aspose.pdf.ai/choice/message/) { get; set; } | Obtient ou définit un message de complétion de chat généré par le modèle. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/choice/tostring/)() | Renvoie le contenu du choix sous forme de chaîne. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


