---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Enum PdfFileEditorConcatenateCorruptedFileAction de Aspose.Pdf.Facades. Acción realizada cuando se encuentra un archivo corrupto en el proceso de concatenación
type: docs
weight: 4470
url: /es/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## Enumeración PdfFileEditor.ConcatenateCorruptedFileAction

Acción realizada cuando se encuentra un archivo corrupto en el proceso de concatenación.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| StopWithError | `0` | Si se encuentra un archivo corrupto, detenga el proceso de concatenación y devuelva un error. |
| ConcatenateIgnoringCorrupted | `1` | Si se encuentra un archivo corrupto, no detenga la concatenación y no procese el archivo corrupto. La lista de archivos corruptos es accesible en la propiedad Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Cuando se encuentra un objeto corrupto en el documento fuente, el proceso no se detendrá y solo se ignorará el objeto corrupto. |

### Ver También

* clase [PdfFileEditor](../pdffileeditor/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../)