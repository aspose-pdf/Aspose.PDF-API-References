---
title: "Clase Aspose::Pdf::Annotations::TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Annotations::TextAnnotation. Representa una anotación de texto que es una ''nota adhesiva'' adjunta a un punto en el documento PDF en C++."
type: docs
weight: 11100
url: /es/cpp/aspose.pdf.annotations/textannotation/
---
## TextAnnotation class


Representa una anotación de texto que es una 'nota adhesiva' adjunta a un punto en el documento PDF.

```cpp
class TextAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Sobrescribe la definición en la clase base con un cuerpo vacío. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_Icon](./get_icon/)() | Obtiene un ícono que se usará al mostrar la anotación. |
| [get_Open](./get_open/)() | Obtiene una bandera que indica si la anotación debe mostrarse inicialmente abierta. |
| [set_Icon](./set_icon/)(TextIcon) | Establece un ícono que se usará al mostrar la anotación. |
| [set_Open](./set_open/)(bool) | Establece una bandera que indica si la anotación debe mostrarse inicialmente abierta. |
| [TextAnnotation](./textannotation/)(const System::SharedPtr\<Document\>\&) | Constructor para anotación cuando se usa en Generator. |
| [TextAnnotation](./textannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Crea una nueva anotación [Text](../../aspose.pdf.text/) en la página especificada. |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
