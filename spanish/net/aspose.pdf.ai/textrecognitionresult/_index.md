---
title: "Clase TextRecognitionResult"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Clase Aspose.Pdf.AI.TextRecognitionResult. Representa los resultados OCR agregados para un único documento fuente"
type: docs
weight: 1180
url: /es/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

Representa los resultados OCR agregados para un único documento fuente.

```csharp
public class TextRecognitionResult
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | Una lista que contiene los resultados OCR detallados para cada página del documento. Para archivos de una sola imagen, esta lista normalmente contendrá una entrada OcrDetail con PageNumber = 1. |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | Indica si OCR fue exitoso para TODAS las páginas de este documento. False si algún OcrDetail en OcrDetails tiene Success = false. |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | Identificador del archivo fuente (p. ej., la ruta completa o un nombre único). |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | Un mensaje de error consolidado si OverallSuccess es false, o un resumen si alguna página falló. Null si OverallSuccess es true. |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | Obtiene o establece las estadísticas totales de uso para procesar este documento (todas las páginas). |

### Ver también

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


