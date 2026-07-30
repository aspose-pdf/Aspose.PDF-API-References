---
title: "Classe TextRecognitionResult"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.TextRecognitionResult. Représente les résultats OCR agrégés pour un seul document source"
type: docs
weight: 1180
url: /fr/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

Représente les résultats agrégés de l'OCR pour un seul document source.

```csharp
public class TextRecognitionResult
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | Une liste contenant les résultats OCR détaillés pour chaque page du document. Pour les fichiers à image unique, cette liste contiendra généralement une entrée OcrDetail avec PageNumber = 1. |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | Indique si l'OCR a réussi pour TOUTES les pages de ce document. Faux si un OcrDetail dans OcrDetails a Success = false. |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | Identifiant du fichier source (par ex., le chemin complet ou un nom unique). |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | Un message d'erreur consolidé si OverallSuccess est false, ou un résumé si une page a échoué. Null si OverallSuccess est true. |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | Obtient ou définit les statistiques d'utilisation totales pour le traitement de ce document (toutes les pages). |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


