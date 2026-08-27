---
title: "Classe TruncationStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.TruncationStrategy. Représente la stratégie de troncature qui contrôle la façon dont un fil sera tronqué avant l'exécution."
type: docs
weight: 1330
url: /fr/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

Représente la stratégie de troncature qui contrôle la façon dont un fil sera tronqué avant l'exécution.

```csharp
public class TruncationStrategy
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Obtient ou définit le nombre des messages les plus récents du fil lors de la construction du contexte pour l'exécution. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Obtient ou définit la stratégie de troncature à utiliser pour le fil. La valeur par défaut est auto. Si elle est définie sur last_messages, le fil sera tronqué aux n messages les plus récents du fil. Lorsqu'elle est définie sur auto, les messages du milieu du fil seront supprimés pour respecter la longueur de contexte du modèle, max_prompt_tokens. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


