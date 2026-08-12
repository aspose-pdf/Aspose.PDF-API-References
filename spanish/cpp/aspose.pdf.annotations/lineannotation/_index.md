---
title: "Clase Aspose::Pdf::Annotations::LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Annotations::LineAnnotation. Clase que representa una anotación de línea en C++."
type: docs
weight: 5700
url: /es/cpp/aspose.pdf.annotations/lineannotation/
---
## LineAnnotation class


Clase que representa una anotación de línea.

```cpp
class LineAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un visitante para el procesamiento de anotaciones. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Actualiza los puntos de inicio y fin, según la transformación de la matriz. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_CaptionOffset](./get_captionoffset/)() | Obtiene el desplazamiento del texto del título desde su posición normal. |
| [get_CaptionPosition](./get_captionposition/)() | Obtiene la posición del título de la anotación. |
| [get_Ending](./get_ending/)() | Obtiene el punto final de la línea. |
| [get_EndingStyle](./get_endingstyle/)() | Obtiene el estilo de terminación para el punto final de la línea. |
| [get_Intent](./get_intent/)() | Obtiene la intención de la anotación de línea. |
| [get_InteriorColor](./get_interiorcolor/)() | Obtiene el color interior de la anotación. |
| [get_LeaderLine](./get_leaderline/)() | Obtiene la longitud de la línea guía. |
| [get_LeaderLineExtension](./get_leaderlineextension/)() | Obtiene la longitud de la extensión de la línea guía. |
| [get_LeaderLineOffset](./get_leaderlineoffset/)() | Obtiene el desplazamiento de la línea guía. |
| [get_Measure](./get_measure/)() | [Measure](../measure/) unidades especificadas para esta anotación. |
| [get_ShowCaption](./get_showcaption/)() | Obtiene la bandera booleana que determina si el contenido debe mostrarse como subtítulo. |
| [get_Starting](./get_starting/)() | Obtiene el punto de inicio de la línea. |
| [get_StartingStyle](./get_startingstyle/)() | Obtiene el estilo de terminación de línea para el punto de inicio de la línea. |
| [LineAnnotation](./lineannotation/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) | Constructor para usar con Generator. |
| [LineAnnotation](./lineannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) | Crea una nueva anotación de Línea en la página especificada. |
| [set_CaptionOffset](./set_captionoffset/)(const System::SharedPtr\<Point\>\&) | Establece el desplazamiento del texto del subtítulo desde su posición normal. |
| [set_CaptionPosition](./set_captionposition/)(Aspose::Pdf::Annotations::CaptionPosition) | Establece la posición del subtítulo de la anotación. |
| [set_Ending](./set_ending/)(const System::SharedPtr\<Point\>\&) | Establece el punto final de la línea. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Establece el estilo de terminación para el punto final de la línea. |
| [set_Intent](./set_intent/)(LineIntent) | Establece la intención de la anotación de línea. |
| [set_InteriorColor](./set_interiorcolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Establece el color interior de la anotación. |
| [set_LeaderLine](./set_leaderline/)(double) | Establece la longitud de la línea guía. |
| [set_LeaderLineExtension](./set_leaderlineextension/)(double) | Establece la longitud de la extensión de la línea guía. |
| [set_LeaderLineOffset](./set_leaderlineoffset/)(double) | Establece el desplazamiento de la línea guía. |
| [set_Measure](./set_measure/)(const System::SharedPtr\<Aspose::Pdf::Annotations::Measure\>\&) | [Measure](../measure/) unidades especificadas para esta anotación. |
| [set_ShowCaption](./set_showcaption/)(bool) | Establece la bandera booleana que determina si el contenido debe mostrarse como subtítulo. |
| [set_Starting](./set_starting/)(const System::SharedPtr\<Point\>\&) | Establece el punto de inicio de la línea. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Establece el estilo de terminación de línea para el punto de inicio de la línea. |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
