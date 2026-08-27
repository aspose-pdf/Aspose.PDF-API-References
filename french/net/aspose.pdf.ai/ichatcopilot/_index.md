---
title: "Interface IChatCopilot"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Interface Aspose.Pdf.AI.IChatCopilot. Représente un copilote de chat pour interagir avec des documents via des modèles d'IA"
type: docs
weight: 490
url: /fr/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot interface

Représente un copilote de chat pour interagir avec des documents via des modèles IA.

```csharp
public interface IChatCopilot : IAICopilot
```

## Méthodes

| Nom | Description |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Supprime le contexte de façon asynchrone. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Obtient de façon asynchrone une réponse pour la liste de messages donnée. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Obtient de façon asynchrone une réponse pour le message donné. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Enregistre de façon asynchrone le contexte dans un fichier JSON. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Enregistre de façon asynchrone les réponses pour la liste de messages donnée dans un fichier PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Enregistre de façon asynchrone la réponse pour le message donné dans un fichier PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Enregistre de façon asynchrone les réponses pour la liste de messages donnée dans un fichier au format spécifié. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Enregistre de façon asynchrone la réponse pour le message donné dans un fichier au format spécifié. |

### Voir aussi

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


