---
title: "Aspose::Pdf::Annotations::LinkAnnotation clase"
linktitle: "LinkAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::LinkAnnotation clase. Representa ya sea un enlace hipervínculo a un destino en otra parte del documento o una acción a realizar en C++."
type: docs
weight: 6000
url: /es/cpp/aspose.pdf.annotations/linkannotation/
---
## LinkAnnotation class


Representa ya sea un enlace hipervínculo a un destino en otra parte del documento o una acción a realizar.

```cpp
class LinkAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [get_Action](./get_action/)() | Una acción a realizar cuando la anotación de enlace se activa. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_Destination](./get_destination/)() | Un destino que se mostrará cuando la anotación se active. |
| [get_Highlighting](./get_highlighting/)() | El efecto visual que se usará cuando el botón del ratón se presione o mantenga pulsado dentro de su área activa. |
| [LinkAnnotation](./linkannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Crea una nueva anotación de enlace en la página especificada. |
| [set_Action](./set_action/)(const System::SharedPtr\<PdfAction\>\&) | Una acción a realizar cuando la anotación de enlace se activa. |
| [set_Destination](./set_destination/)(const System::SharedPtr\<IAppointment\>\&) | Un destino que se mostrará cuando la anotación se active. |
| [set_Highlighting](./set_highlighting/)(HighlightingMode) | El efecto visual que se usará cuando el botón del ratón se presione o mantenga pulsado dentro de su área activa. |
## Ver también

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
