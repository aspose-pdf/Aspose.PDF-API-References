---
title: "Aspose::Pdf::Annotations::TextMarkupAnnotation clase"
linktitle: "TextMarkupAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Annotations::TextMarkupAnnotation. Clase base abstracta para anotaciones de marcado de texto en C++."
type: docs
weight: 11300
url: /es/cpp/aspose.pdf.annotations/textmarkupannotation/
---
## TextMarkupAnnotation class


Clase base abstracta para anotaciones de marcado de texto.

```cpp
class TextMarkupAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Actualiza los QuadPoints, de acuerdo con la transformación de la matriz. |
| [get_QuadPoints](./get_quadpoints/)() | Obtiene una matriz de puntos que especifica las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación. |
| [GetMarkedText](./getmarkedtext/)() | Obtiene el texto bajo la anotación de marcado como cadena. |
| [GetMarkedTextFragments](./getmarkedtextfragments/)() | Obtiene el texto bajo la anotación de marcado como [TextFragmentCollection](../). |
| [set_QuadPoints](./set_quadpoints/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Establece una matriz de puntos que especifica las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación. |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
