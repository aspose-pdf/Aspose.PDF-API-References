---
title: "Aspose::Pdf::Annotations::PopupAnnotation clase"
linktitle: "PopupAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::PopupAnnotation clase. Representa la anotación emergente que muestra texto en una ventana emergente para la entrada y edición en C++."
type: docs
weight: 8800
url: /es/cpp/aspose.pdf.annotations/popupannotation/
---
## PopupAnnotation class


Representa la anotación emergente que muestra texto en una ventana emergente para la introducción y edición.

```cpp
class PopupAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_Open](./get_open/)() | Obtiene una bandera que indica si la anotación emergente debe mostrarse inicialmente abierta. |
| [get_Parent](./get_parent/)() | Obtiene la anotación padre con la que se asociará esta anotación emergente. Si esta entrada está presente, los campos Contents, M, C y T de la anotación padre sobrescribirán los de la propia anotación emergente. |
| [PopupAnnotation](./popupannotation/)(const System::SharedPtr\<Document\>\&) | Constructor. para usar en Generator. |
| [PopupAnnotation](./popupannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Crea una nueva anotación emergente en la página especificada. |
| [set_Open](./set_open/)(bool) | Establece una bandera que indica si la anotación emergente debe mostrarse inicialmente abierta. |
| [set_Parent](./set_parent/)(const System::SharedPtr\<Annotation\>\&) | Establece la anotación padre con la que se asociará esta anotación emergente. Si esta entrada está presente, los campos Contents, M, C y T de la anotación padre sobrescribirán los de la propia anotación emergente. |
## Ver también

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
