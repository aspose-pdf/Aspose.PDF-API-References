---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateText method"
linktitle: "CreateText"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateText method. Crea una anotación de texto en un documento PDF en C++."
type: docs
weight: 2500
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor::CreateText method


Crea una anotación de texto en el documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateText(System::Drawing::Rectangle rect, const System::String &title, const System::String &contents, bool open, const System::String &icon, int32_t page)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| title | const System::String\& | El título de la anotación. |
| contenido | const System::String\& | El contenido de la anotación. |
| abierto | bool | Una bandera que especifica si la anotación debe mostrarse inicialmente abierta. |
| icon | const System::String\& | El nombre de un icono que se usará al mostrar la anotación. Este valor puede ser: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| página | int32_t | El número de la página original donde se creará la anotación de texto. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
