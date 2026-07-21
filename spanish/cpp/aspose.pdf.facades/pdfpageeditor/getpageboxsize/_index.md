---
title: "Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize método"
linktitle: "GetPageBoxSize"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize método. Devuelve el tamaño del cuadro especificado en el documento en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor::GetPageBoxSize method


Devuelve el tamaño del cuadro especificado en el documento.

```cpp
System::Drawing::Rectangle Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize(int32_t page, const System::String &pageBoxName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | int32_t | [Page](../../../aspose.pdf/page/) índice. [Document](../../../aspose.pdf/document/) las páginas están numeradas a partir de 1. |
| pageBoxName | const System::String\& | Nombre del tipo de cuadro. Los valores válidos son: "art", "bleed", "crop", "media", "trim". |

### ReturnValue

[Rectangle](../../../aspose.pdf/rectangle/) which contains requested box.

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfPageEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
