---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.AI.IChatCopilot. Représente un copilote de chat pour interagir avec des documents via des modèles d'IA
type: docs
weight: 470
url: /fr/net/aspose.pdf.ai/ichatcopilot/
---
## Interface IChatCopilot

Représente un copilote de chat pour interagir avec des documents via des modèles d'IA.

```csharp
public interface IChatCopilot : IAICopilot
```

## Méthodes

| Nom | Description |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Supprime le contexte de manière asynchrone. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Obtient de manière asynchrone une réponse pour la liste donnée de messages. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Obtient de manière asynchrone une réponse pour le message donné. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Enregistre de manière asynchrone le contexte dans un fichier JSON. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Enregistre de manière asynchrone les réponses pour la liste donnée de messages dans un fichier PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Enregistre de manière asynchrone la réponse pour le message donné dans un fichier PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Enregistre de manière asynchrone les réponses pour la liste donnée de messages dans un fichier avec le format spécifié. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Enregistre de manière asynchrone la réponse pour le message donné dans un fichier avec le format spécifié. |

### Voir aussi

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)