---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction método"
linktitle: "CreateBookmarksAction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction método. Crea un marcador con la acción especificada en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor::CreateBookmarksAction method


Crea un marcador con la acción especificada.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction(const System::String &title, System::Drawing::Color color, bool boldFlag, bool italicFlag, const System::String &file, const System::String &actionType, const System::String &destination)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| title | const System::String\& | El título del marcador. |
| color | System::Drawing::Color | El color del título del marcador. |
| boldFlag | bool | La bandera de atributo en negrita. |
| italicFlag | bool | La bandera de atributo en cursiva. |
| file | const System::String\& | Otro archivo o aplicación requerida cuando el tipo de acción es "GoToR" o "Launch". |
| actionType | const System::String\& | El tipo de acción. El valor puede ser: "GoToR", "Launch", "GoTo", "URI". |
| destination | const System::String\& | El destino local o destino remoto o URL. |

## Ver también

* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
