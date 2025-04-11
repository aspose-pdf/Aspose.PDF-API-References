---
title: Class MarkupParagraph
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.MarkupParagraph. Representa un párrafo
type: docs
weight: 10630
url: /es/net/aspose.pdf.text/markupparagraph/
---
## Clase MarkupParagraph

Representa un párrafo.

```csharp
public sealed class MarkupParagraph
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | Lista de números de página en los que se continúa el párrafo. Coincidirá con la página donde comenzó el párrafo si se continúa en la siguiente columna de la misma página. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | Colección de objetos [`TextFragment`](../textfragment/) no vacíos del párrafo. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | Líneas del párrafo. Cada línea está representada por una lista de fragmentos de texto. |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | Puntos del polígono que describe el párrafo. El punto de inicio es la esquina inferior izquierda del párrafo. Y los siguientes puntos están en secuencia antihoraria. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | Puntos del polígono secundario que describe la continuación del párrafo. No será nulo si el párrafo se continúa en la siguiente columna o página. El punto de inicio es la esquina inferior izquierda del párrafo. Y los siguientes puntos están en secuencia antihoraria. |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | Obtiene o establece el texto del párrafo. |

### Ver También

* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblaje [Aspose.PDF](../../)