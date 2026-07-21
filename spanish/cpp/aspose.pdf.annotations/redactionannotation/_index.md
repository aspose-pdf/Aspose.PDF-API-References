---
title: "Aspose::Pdf::Annotations::RedactionAnnotation clase"
linktitle: "RedactionAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::RedactionAnnotation clase. Representa la anotación Redact en C++."
type: docs
weight: 9200
url: /es/cpp/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class


Representa una anotación de redacción.

```cpp
class RedactionAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [Flatten](./flatten/)() override | Aplana la anotación, es decir, elimina la anotación y agrega su contenido. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_BorderColor](./get_bordercolor/)() | Obtiene el color del borde que se dibuja cuando la redacción no está activa. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Obtiene la cadena de apariencia predeterminada que se usará al formatear el texto. |
| [get_FillColor](./get_fillcolor/)() | Obtiene el color para rellenar la anotación. |
| [get_FontSize](./get_fontsize/)() const | Obtiene el tamaño de fuente para OverlayText. |
| [get_OverlayText](./get_overlaytext/)() | Obtiene el texto para imprimir en la anotación redact. |
| [get_QuadPoint](./get_quadpoint/)() | Una matriz de números 8xN que especifica las coordenadas de la región de contenido que se pretende eliminar. |
| [get_Repeat](./get_repeat/)() | Si es verdadero, el texto superpuesto se repetirá en la anotación. |
| [get_TextAlignment](./get_textalignment/)() | Obtiene. Alineación de Overlay [Text](../../aspose.pdf.text/). |
| [Redact](./redact/)() | Aplana la anotación y redacta el contenido de la página (es decir, elimina texto e imagen bajo la anotación redactada). |
| [RedactionAnnotation](./redactionannotation/)(const System::SharedPtr\<Document\>\&) | Constructor para [RedactionAnnotation](./). Para usar en Generator. |
| [RedactionAnnotation](./redactionannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Constructor para RedactAnnotation. |
| [set_BorderColor](./set_bordercolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Establece el color del borde que se dibuja cuando la redacción no está activa. |
| [set_DefaultAppearance](./set_defaultappearance/)(const System::String\&) | Establece la cadena de apariencia predeterminada que se usará al formatear el texto. |
| [set_FillColor](./set_fillcolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Establece el color para rellenar la anotación. |
| [set_FontSize](./set_fontsize/)(float) | Establece el tamaño de fuente para OverlayText. |
| [set_OverlayText](./set_overlaytext/)(const System::String\&) | Establece el texto para imprimir en la anotación redact. |
| [set_QuadPoint](./set_quadpoint/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Una matriz de números 8xN que especifica las coordenadas de la región de contenido que se pretende eliminar. |
| [set_Repeat](./set_repeat/)(bool) | Si es verdadero, el texto superpuesto se repetirá en la anotación. |
| [set_TextAlignment](./set_textalignment/)(Aspose::Pdf::HorizontalAlignment) | Establece. Alineación de Overlay [Text](../../aspose.pdf.text/). |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
