---
title: MarkupParagraph
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa un párrafo.
type: docs
weight: 6810
url: /es/net/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class

Representa un párrafo.

```csharp
public sealed class MarkupParagraph
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers) { get; } | Lista de números de página en los que continúa el párrafo. Coincidirá con la página donde comenzó el párrafo si continúa en la siguiente columna de la misma página. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments) { get; } | Colección de no vacío[`TextFragment`](../textfragment) objetos del párrafo. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines) { get; } | Líneas de párrafo. Cada línea representada por una lista de fragmentos de texto. |
| [Points](../../aspose.pdf.text/markupparagraph/points) { get; } | Puntos del polígono que describe el párrafo. El punto de inicio es la esquina inferior izquierda del párrafo. Y los siguientes puntos están en secuencia en sentido contrario a las agujas del reloj. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints) { get; } | Los puntos del polígono secundario describen la continuación del párrafo. No será nulo si el párrafo continúa en la siguiente columna o página. El punto de inicio es la esquina inferior izquierda del párrafo. Y los siguientes puntos están en secuencia en sentido contrario a las agujas del reloj. |
| [Text](../../aspose.pdf.text/markupparagraph/text) { get; } | ObtieneString objeto de texto que el[`MarkupParagraph`](../markupparagraph) objeto representa. |

### Ver también

* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
