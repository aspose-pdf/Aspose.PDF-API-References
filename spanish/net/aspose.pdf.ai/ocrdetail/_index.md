---
title: "Clase OcrDetail"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Aspose.Pdf.AI.OcrDetail class. Representa el resultado OCR para una sola página de un documento o un solo archivo de imagen"
type: docs
weight: 860
url: /es/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

Representa el resultado OCR para una sola página de un documento o un solo archivo de imagen.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OcrDetail](ocrdetail/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | Un mensaje de error que describe por qué OCR falló en esta página, si Success es false. Null de lo contrario. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | El contenido de texto extraído de la página. Null si Success es false o no se encontró texto. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | El número de página basado en 1 dentro del documento fuente. Para imágenes de una sola página, siempre será 1. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | Indica si la extracción OCR para esta página específica fue exitosa. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | Obtiene o establece las estadísticas de uso. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | Compara la instancia actual de OcrDetail con otro objeto OcrDetail basado en su propiedad PageNumber. |

### Ver también

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


