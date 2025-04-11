---
title: Interface ISummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.AI.ISummaryCopilot. Représente un copilote de résumé pour générer des résumés pour des documents en utilisant des modèles d'IA
type: docs
weight: 590
url: /fr/net/aspose.pdf.ai/isummarycopilot/
---
## Interface ISummaryCopilot

Représente un copilote de résumé pour générer des résumés pour des documents en utilisant des modèles d'IA.

```csharp
public interface ISummaryCopilot : IAICopilot
```

## Méthodes

| Nom | Description |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/isummarycopilot/getsummaryasync/)(CancellationToken?) | Obtient un résumé de manière asynchrone. |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) | Obtient un document PDF de résumé de manière asynchrone. |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) | Obtient un document PDF de résumé pour les informations de page spécifiées de manière asynchrone. |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) | Enregistre le résumé dans un fichier PDF de manière asynchrone. |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) | Enregistre le résumé dans un fichier avec le format spécifié de manière asynchrone. |

### Voir aussi

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)