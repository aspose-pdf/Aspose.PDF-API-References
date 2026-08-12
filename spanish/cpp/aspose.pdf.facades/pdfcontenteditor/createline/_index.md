---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateLine método"
linktitle: "CreateLine"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateLine método. Crea una anotación de línea en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor::CreateLine method


Crea una anotación de línea.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLine(System::Drawing::Rectangle rect, const System::String &contents, float x1, float y1, float x2, float y2, int32_t page, int32_t border, System::Drawing::Color clr, const System::String &borderStyle, const System::ArrayPtr<int32_t> &dashArray, const System::ArrayPtr<System::String> &LEArray)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contenido | const System::String\& | El contenido de la anotación. |
| x1 | float | La coordenada horizontal inicial de la línea. |
| y1 | float | La coordenada vertical inicial de la línea. |
| x2 | float | La coordenada horizontal final de la línea. |
| y2 | float | La coordenada vertical final de la línea. |
| página | int32_t | El número de la página original donde se creará la anotación. |
| borde | int32_t | El ancho del borde en puntos. Si este valor es 0 no se dibuja ningún borde. El valor predeterminado es 1. |
| clr | System::Drawing::Color | El color de la línea. |
| borderStyle | const System::String\& | El estilo de borde que especifica el ancho y el patrón de guiones a usar al dibujar la línea. Este valor puede ser: \"S\" (Sólido), \"D\" (Discontinuo), \"B\" (Biselado), \"I\" (Inset), \"U\" (Subrayado). |
| dashArray | const System::ArrayPtr\<int32_t\>\& | Una matriz de guiones que define un patrón de guiones y espacios a usar al dibujar un borde discontinuo. Si se usa, borderSyle debe establecerse en \"D\". |
| LEArray | const System::ArrayPtr\<System::String\>\& | Una matriz de dos valores que especifican respectivamente el estilo de inicio y fin de la línea dibujada. Los valores pueden ser: \"Square\", \"Circle\", \"Diamond\", \"OpenArrow\", \"ClosedArrow\", \"None\", \"Butt\", \"ROpenArrow\", \"RClosedArrow\", \"Slash\". |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
