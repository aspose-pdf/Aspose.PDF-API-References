---
title: "Aspose::Pdf::Annotations::InkAnnotation class"
linktitle: "InkAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::InkAnnotation class. Representa un \"garabato\" a mano alzada compuesto por una o más rutas disjuntas en C++."
type: docs
weight: 5200
url: /es/cpp/aspose.pdf.annotations/inkannotation/
---
## InkAnnotation class


Representa un garabato a mano alzada "scribble" compuesto por una o más rutas disjuntas.

```cpp
class InkAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Actualiza los puntos en InkList, de acuerdo con la transformación de la matriz. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_CapStyle](./get_capstyle/)() | Estilo de los finales de línea de la anotación de tinta. |
| [get_InkList](./get_inklist/)() | Obtiene la lista de gestos que son líneas independientes y que se representan mediante matrices de [Point](../../aspose.pdf/point/)[] . |
| [InkAnnotation](./inkannotation/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) | Constructor para la anotación de tinta para Generator. |
| [InkAnnotation](./inkannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) | Crea una nueva anotación de tinta en la página especificada. |
| [set_CapStyle](./set_capstyle/)(Aspose::Pdf::Annotations::CapStyle) | Estilo de los finales de línea de la anotación de tinta. |
| [set_InkList](./set_inklist/)(const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) | Establece la lista de gestos que son líneas independientes y que se representan mediante matrices de [Point](../../aspose.pdf/point/)[]. |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
