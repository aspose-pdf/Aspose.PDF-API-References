---
title: "Aspose::Pdf::Annotations::FreeTextAnnotation class"
linktitle: "FreeTextAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::FreeTextAnnotation class. Representa una anotación de texto libre que muestra texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene estado abierto o cerrado; en lugar de mostrarse en una ventana emergente, el texto siempre es visible en C++."
type: docs
weight: 4000
url: /es/cpp/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class


Representa una anotación de texto libre que muestra el texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene estado abierto o cerrado; en lugar de mostrarse en una ventana emergente, el texto siempre es visible.

```cpp
class FreeTextAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [FreeTextAnnotation](./freetextannotation/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>\&) | Constructor para usar con Generator. |
| [FreeTextAnnotation](./freetextannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>\&) | Crea una nueva anotación FreeText en la página especificada. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_Callout](./get_callout/)() | Matriz de puntos que especifican la línea de llamada. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Obtiene la cadena de apariencia predeterminada que se usará al formatear el texto. |
| [get_DefaultAppearanceObject](./get_defaultappearanceobject/)() | Objeto que representa la apariencia predeterminada de la anotación FreeText. |
| [get_DefaultStyle](./get_defaultstyle/)() | Obtiene una cadena de estilo predeterminada. |
| [get_EndingStyle](./get_endingstyle/)() | Obtiene el estilo de terminación de línea para el punto final de la línea. |
| [get_Intent](./get_intent/)() | Obtiene la intención de la anotación de texto libre. |
| [get_Justification](./get_justification/)() | Obtiene o establece un código que especifica la forma de justificación (quadding) que se usará al mostrar el texto de la anotación. |
| [get_Rotate](./get_rotate/)() | Ángulo de rotación de la anotación. |
| [get_StartingStyle](./get_startingstyle/)() | Obtiene el estilo de terminación de línea para el punto final de la línea. OThis property is obsolete, please use EndingStyle. |
| [get_TextRectangle](./get_textrectangle/)() | [Rectangle](../../aspose.pdf/rectangle/) que describe las diferencias numéricas entre dos rectángulos: la entrada Rect de la anotación y un rectángulo contenido dentro de ese rectángulo. El rectángulo interno es donde se debe mostrar el texto de la anotación. |
| [get_TextStyle](./get_textstyle/)() | Obtiene el estilo del texto en la apariencia. Cuando el estilo del texto cambia, la apariencia del texto se actualiza. |
| [set_Callout](./set_callout/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Matriz de puntos que especifican la línea de llamada. |
| [set_DefaultAppearance](./set_defaultappearance/)(const System::String\&) | Establece la cadena de apariencia predeterminada que se usará al formatear el texto. |
| [set_DefaultStyle](./set_defaultstyle/)(const System::String\&) | Establece una cadena de estilo predeterminada. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Establece el estilo de terminación de línea para el punto final de la línea. |
| [set_Intent](./set_intent/)(FreeTextIntent) | Establece la intención de la anotación de texto libre. |
| [set_Justification](./set_justification/)(Aspose::Pdf::Annotations::Justification) | Obtiene o establece un código que especifica la forma de justificación (quadding) que se usará al mostrar el texto de la anotación. |
| [set_Rotate](./set_rotate/)(Rotation) | Ángulo de rotación de la anotación. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Establece el estilo de terminación de línea para el punto final de la línea. OThis property is obsolete, please use EndingStyle. |
| [set_TextRectangle](./set_textrectangle/)(const System::SharedPtr\<Rectangle\>\&) | [Rectangle](../../aspose.pdf/rectangle/) que describe las diferencias numéricas entre dos rectángulos: la entrada Rect de la anotación y un rectángulo contenido dentro de ese rectángulo. El rectángulo interno es donde se debe mostrar el texto de la anotación. |
| [set_TextStyle](./set_textstyle/)(const System::SharedPtr\<Aspose::Pdf::Annotations::TextStyle\>\&) | Establece el estilo del texto en la apariencia. Cuando el estilo del texto cambia, la apariencia del texto se actualiza. |
| [SetTextStyle](./settextstyle/)(RichTextFontStyles, const System::String\&, double, System::Drawing::Color) | Establece el formato determinado por el parámetro textStyle para todo el texto de la anotación. |
| [SetTextStyle](./settextstyle/)(int32_t, int32_t, RichTextFontStyles) | Establece el formato determinado por el parámetro textStyle para un fragmento de texto desde el índice fromInd hasta el índice toInd. |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
