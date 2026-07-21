---
title: "Enumeración Aspose::Pdf::Facades::PdfFileEditor::ConcatenateCorruptedFileAction"
linktitle: "ConcatenateCorruptedFileAction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Enumeración Aspose::Pdf::Facades::PdfFileEditor::ConcatenateCorruptedFileAction. Acción realizada cuando se encuentra un archivo corrupto en el proceso de concatenación en C++."
type: docs
weight: 7200
url: /es/cpp/aspose.pdf.facades/pdffileeditor/concatenatecorruptedfileaction/
---
## ConcatenateCorruptedFileAction enum


Acción realizada cuando se encontró un archivo corrupto en el proceso de concatenación.

```cpp
enum class ConcatenateCorruptedFileAction
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| StopWithError | 0 | Si se encuentra un archivo corrupto, entonces se detiene el proceso de concatenación y se devuelve un error. |
| ConcatenateIgnoringCorrupted | 1 | Si se encuentra un archivo corrupto, entonces no se detiene la concatenación y no se procesa el archivo corrupto. La lista de archivos corruptos es accesible en la propiedad Failures. |
| ConcatenateIgnoringCorruptedObjects | 2 | Cuando se encuentra un objeto corrupto en el documento fuente, el proceso no se detendrá y solo se ignorará el objeto corrupto. |

## Ver también

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
