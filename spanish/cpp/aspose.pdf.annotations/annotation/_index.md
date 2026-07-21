---
title: "Clase Aspose::Pdf::Annotations::Annotation"
linktitle: "Anotación"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Annotations::Annotation. Clase que representa un objeto de anotación en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.annotations/annotation/
---
## Annotation class


Clase que representa un objeto de anotación.

```cpp
class Annotation : public Aspose::Pdf::BaseParagraph
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) | Acepta un visitante para el procesamiento de anotaciones. |
| virtual [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) | Actualiza los parámetros y la apariencia, según la transformación de la matriz. |
| virtual [Flatten](./flatten/)() | Coloca el contenido de la anotación directamente en la página, el objeto de anotación será eliminado. |
| [get_Actions](./get_actions/)() | Obtiene la lista de acciones de anotación. |
| virtual [get_ActiveState](./get_activestate/)() | Obtiene el estado actual de apariencia de la anotación. |
| [get_Alignment](./get_alignment/)() | [Annotation](./) alineación. Esta propiedad está obsoleta. Use HorizontalAligment en su lugar. |
| virtual [get_AnnotationType](./get_annotationtype/)() | Obtiene el tipo de anotación. |
| [get_Appearance](./get_appearance/)() | Obtiene el diccionario de apariencia de la anotación. |
| [get_Border](./get_border/)() const | Obtiene las características del borde de la anotación. [Border](../border/) |
| [get_Characteristics](./get_characteristics/)() | Obtiene las características de la anotación. |
| [get_Color](./get_color/)() | Obtiene el color de la anotación. |
| [get_Contents](./get_contents/)() | Obtiene el texto de la anotación. |
| [get_Flags](./get_flags/)() | Indicadores de la anotación. |
| [get_FullName](./get_fullname/)() | Obtiene el nombre completo calificado de la anotación. |
| virtual [get_Height](./get_height/)() | Obtiene la altura de la anotación. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Obtiene la alineación de texto para la anotación. |
| [get_Modified](./get_modified/)() | Obtiene la fecha y hora en que la anotación fue modificada recientemente. |
| [get_Name](./get_name/)() | Obtiene el nombre de la anotación en la página. |
| virtual [get_PageIndex](./get_pageindex/)() | Obtiene el índice de la página que contiene la anotación. |
| virtual [get_Rect](./get_rect/)() | Obtiene el rectángulo de la anotación. |
| [get_States](./get_states/)() | Obtiene el diccionario de apariencia de la anotación. |
| [get_TextHorizontalAlignment](./get_texthorizontalalignment/)() | Obtiene la alineación de texto para la anotación. |
| static [get_UpdateAppearanceOnConvert](./get_updateappearanceonconvert/)() | Si es verdadero, la apariencia de la anotación se actualizará antes de convertir el documento PF en imagen. Esto permite convertir los campos correctamente pero probablemente requiera más tiempo. |
| static [get_UseFontSubset](./get_usefontsubset/)() | Si esta propiedad se establece en verdadero, las fuentes se agregarán al documento como subconjuntos. El valor predeterminado es verdadero. |
| virtual [get_Width](./get_width/)() | Obtiene el ancho de la anotación. |
| [GetRectangle](./getrectangle/)(bool) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| virtual [set_ActiveState](./set_activestate/)(System::String) | Establece el estado de apariencia de la anotación actual. |
| [set_Alignment](./set_alignment/)(TextAlignment) | [Annotation](./) alineación. Esta propiedad está obsoleta. Use HorizontalAligment en su lugar. |
| [set_Border](./set_border/)(const System::SharedPtr\<Aspose::Pdf::Annotations::Border\>\&) | Establece las características del borde de la anotación. [Border](../border/) |
| [set_Color](./set_color/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Establece el color de la anotación. |
| [set_Contents](./set_contents/)(const System::String\&) | Establece el texto de la anotación. |
| [set_Flags](./set_flags/)(AnnotationFlags) | Indicadores de la anotación. |
| virtual [set_Height](./set_height/)(double) | Establece la altura de la anotación. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Establece la alineación del texto para la anotación. |
| [set_Modified](./set_modified/)(System::DateTime) | Establece la fecha y hora en que la anotación fue modificada recientemente. |
| [set_Name](./set_name/)(const System::String\&) | Establece el nombre de la anotación en la página. |
| virtual [set_Rect](./set_rect/)(System::SharedPtr\<Rectangle\>) | Establece el rectángulo de la anotación. |
| [set_TextHorizontalAlignment](./set_texthorizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Establece la alineación del texto para la anotación. |
| static [set_UpdateAppearanceOnConvert](./set_updateappearanceonconvert/)(bool) | Si es verdadero, la apariencia de la anotación se actualizará antes de convertir el documento PF en imagen. Esto permite convertir los campos correctamente pero probablemente requiera más tiempo. |
| static [set_UseFontSubset](./set_usefontsubset/)(bool) | Si esta propiedad se establece en verdadero, las fuentes se agregarán al documento como subconjuntos. El valor predeterminado es verdadero. |
| virtual [set_Width](./set_width/)(double) | Establece el ancho de la anotación. |
## Ver también

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
