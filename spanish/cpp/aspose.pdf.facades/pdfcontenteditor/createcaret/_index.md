---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateCaret método"
linktitle: "CreateCaret"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateCaret método. Crea una anotación de caret en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor::CreateCaret method


Crea una anotación de cursor.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateCaret(int32_t page, System::Drawing::Rectangle annotRect, System::Drawing::Rectangle caretRect, const System::String &symbol, const System::String &annotContents, System::Drawing::Color color)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int32_t | El número de la página original donde se creará la anotación. |
| annotRect | System::Drawing::Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| caretRect | System::Drawing::Rectangle | Los límites reales del caret subyacente. |
| symbol | const System::String\& | Se asociará un símbolo al caret. El valor puede ser: "P" (Párrafo), "None". |
| annotContents | const System::String\& | El contenido de la anotación. |
| color | System::Drawing::Color | El color de la anotación. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
