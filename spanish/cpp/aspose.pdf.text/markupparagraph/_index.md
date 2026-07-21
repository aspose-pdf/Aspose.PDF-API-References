---
title: "Aspose::Pdf::Text::MarkupParagraph class"
linktitle: "MarkupParagraph"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::MarkupParagraph class. Representa un párrafo en C++."
type: docs
weight: 2100
url: /es/cpp/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class


Representa un párrafo.

```cpp
class MarkupParagraph : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ContinuationPageNumbers](./get_continuationpagenumbers/)() const | Lista de números de página en los que el párrafo continúa. Coincidirá con la página donde el párrafo comenzó si continúa en la siguiente columna de la misma página. |
| [get_Fragments](./get_fragments/)() | [Colección](../../aspose.pdf/collection/) de objetos [TextFragment](../textfragment/) no vacíos del párrafo. |
| [get_Lines](./get_lines/)() const | Líneas del párrafo. Cada línea está representada por una lista de fragmentos de texto. |
| [get_Points](./get_points/)() | Puntos del polígono que describe el párrafo. El punto de inicio es la esquina inferior izquierda del párrafo. Y los siguientes puntos están en secuencia antihoraria. |
| [get_SecondaryPoints](./get_secondarypoints/)() const | Puntos del polígono secundario que describe la continuación del párrafo. No será nulo si el párrafo continúa en la siguiente columna o página. El punto de inicio es la esquina inferior izquierda del párrafo. Y los siguientes puntos están en secuencia antihoraria. |
| [get_Text](./get_text/)() | Obtiene el texto del párrafo. |
| [set_Text](./set_text/)(const System::String\&) | Establece el texto del párrafo. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
