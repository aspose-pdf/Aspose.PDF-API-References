---
title: "Aspose::Pdf::Annotations::ScreenAnnotation clase"
linktitle: "ScreenAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::ScreenAnnotation clase. Una anotación de pantalla que especifica una región de una página en la que se pueden reproducir clips de medios en C++."
type: docs
weight: 9800
url: /es/cpp/aspose.pdf.annotations/screenannotation/
---
## ScreenAnnotation class


Una anotación de pantalla que especifica una región de una página en la que se pueden reproducir clips de medios.

```cpp
class ScreenAnnotation : public Aspose::Pdf::Annotations::Annotation,
                         public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [get_Action](./get_action/)() | Obtiene una acción que se ejecutará cuando la anotación se active. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_Title](./get_title/)() override | Obtiene el título de la anotación de pantalla. |
| [ScreenAnnotation](./screenannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) | Crea una nueva anotación de pantalla en la página especificada. |
| [set_Title](./set_title/)(System::String) override | Establece el título de la anotación de pantalla. |
## Ver también

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
