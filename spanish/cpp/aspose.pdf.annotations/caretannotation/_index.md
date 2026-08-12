---
title: "Aspose::Pdf::Annotations::CaretAnnotation clase"
linktitle: "CaretAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::CaretAnnotation clase. Clase que representa una anotación Caret en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.annotations/caretannotation/
---
## CaretAnnotation class


Clase que representa una anotación de Cursor.

```cpp
class CaretAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [CaretAnnotation](./caretannotation/)(const System::SharedPtr\<Document\>\&) | Constructor para usar en Generator. |
| [CaretAnnotation](./caretannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Crea una nueva anotación Caret en la página especificada. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_Frame](./get_frame/)() | Obtiene el rectángulo del caret. |
| [get_Symbol](./get_symbol/)() | Obtiene el símbolo asociado al caret. |
| [set_Frame](./set_frame/)(const System::SharedPtr\<Rectangle\>\&) | Establece el rectángulo del caret. |
| [set_Symbol](./set_symbol/)(CaretSymbol) | Establece el símbolo asociado al caret. |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
