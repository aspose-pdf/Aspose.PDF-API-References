---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.TruncationStrategy. Représente la stratégie de troncature qui contrôle comment un fil sera tronqué avant l'exécution
type: docs
weight: 1240
url: /fr/net/aspose.pdf.ai/truncationstrategy/
---
## Classe TruncationStrategy

Représente la stratégie de troncature qui contrôle comment un fil sera tronqué avant l'exécution.

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
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Obtient ou définit le nombre de messages les plus récents du fil lors de la construction du contexte pour l'exécution. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Obtient ou définit la stratégie de troncature à utiliser pour le fil. La valeur par défaut est auto. Si définie sur last_messages, le fil sera tronqué aux n messages les plus récents du fil. Lorsqu'elle est définie sur auto, les messages au milieu du fil seront supprimés pour s'adapter à la longueur du contexte du modèle, max_prompt_tokens. |

### Voir aussi

* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)