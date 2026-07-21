---
title: "Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle método"
linktitle: "SetTextStyle"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle método. Establece el formato determinado por el parámetro textStyle para un fragmento de texto desde el índice fromInd hasta el índice toInd en C++."
type: docs
weight: 2500
url: /es/cpp/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## FreeTextAnnotation::SetTextStyle(int32_t, int32_t, RichTextFontStyles) method


Establece el formato determinado por el parámetro textStyle para un fragmento de texto desde el índice fromInd hasta el índice toInd.

```cpp
void Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle(int32_t fromInd, int32_t toInd, RichTextFontStyles textStyles)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fromInd | int32_t | Índice inicial del fragmento de texto (desde 0). |
| toInd | int32_t | Índice final del fragmento de texto (contando desde 0, este no está incluido). |
| textStyles | RichTextFontStyles | Estilo(s) aplicado(s) al fragmento de texto. |

## Ver también

* Enum [RichTextFontStyles](../../richtextfontstyles/)
* Class [FreeTextAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## FreeTextAnnotation::SetTextStyle(RichTextFontStyles, const System::String\&, double, System::Drawing::Color) method


Establece el formato determinado por el parámetro textStyle para todo el texto de la anotación.

```cpp
void Aspose::Pdf::Annotations::FreeTextAnnotation::SetTextStyle(RichTextFontStyles textStyles, const System::String &fontName, double fontSize, System::Drawing::Color fontColor)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Estilo(s) aplicado(s) al texto de la anotación. |
| fontName | const System::String\& | Nombre de fuente aplicado al texto de la anotación. |
| fontSize | double | Tamaño de fuente aplicado al texto de la anotación. |
| fontColor | System::Drawing::Color | Color de fuente aplicado al texto de la anotación. |

## Ver también

* Enum [RichTextFontStyles](../../richtextfontstyles/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [FreeTextAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
