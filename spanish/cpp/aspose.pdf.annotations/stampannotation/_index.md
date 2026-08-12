---
title: "Aspose::Pdf::Annotations::StampAnnotation clase"
linktitle: "StampAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::StampAnnotation clase. Representa una anotación de sello de goma. Este tipo de anotación muestra texto o gráficos que parecen haber sido estampados en la página con un sello de goma en C++."
type: docs
weight: 10700
url: /es/cpp/aspose.pdf.annotations/stampannotation/
---
## StampAnnotation class


Representa una anotación de sello de goma. Este tipo de anotación muestra texto o gráficos que parecen haber sido estampados en la página con un sello de goma.

```cpp
class StampAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta [AnnotationSelector](../annotationselector/) visitante al explorar la colección de anotaciones. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_Icon](./get_icon/)() | Obtiene el icono del sello de goma. |
| [get_Image](./get_image/)() | Obtiene la imagen de la anotación. |
| [set_Icon](./set_icon/)(StampIcon) | Establece el icono del sello de goma. |
| [set_Image](./set_image/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece la imagen de la anotación. |
| [StampAnnotation](./stampannotation/)(const System::SharedPtr\<Document\>\&) | Constructor. |
| [StampAnnotation](./stampannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Crea una nueva anotación [Stamp](../../aspose.pdf/stamp/) en la página especificada. |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
