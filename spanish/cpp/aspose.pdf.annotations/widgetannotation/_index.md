---
title: "Aspose::Pdf::Annotations::WidgetAnnotation clase"
linktitle: "WidgetAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::WidgetAnnotation clase. Clase que representa la anotación de widget en C++."
type: docs
weight: 11800
url: /es/cpp/aspose.pdf.annotations/widgetannotation/
---
## WidgetAnnotation class


Clase que representa una anotación de widget.

```cpp
class WidgetAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta visitante. |
| [get_Actions](./get_actions/)() | Obtiene las acciones de la anotación. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Obtiene la apariencia predeterminada del campo. |
| [get_Exportable](./get_exportable/)() | Obtiene la bandera exportable del campo. |
| [get_Highlighting](./get_highlighting/)() | [Annotation](../annotation/) modo de resaltado. |
| [get_OnActivated](./get_onactivated/)() | Una acción que se realizará cuando la anotación se active. |
| [get_Parent](./get_parent/)() | Obtiene el padre de la anotación. |
| [get_ReadOnly](./get_readonly/)() | Obtiene el estado de solo lectura del campo. |
| [get_Required](./get_required/)() | Obtiene el estado requerido del campo. |
| [GetCheckedStateName](./getcheckedstatename/)() | Devuelve el nombre del estado "checked" según los nombres de estado existentes. |
| [set_DefaultAppearance](./set_defaultappearance/)(const System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>\&) | Establece la apariencia predeterminada del campo. |
| [set_Exportable](./set_exportable/)(bool) | Establece la bandera exportable del campo. |
| [set_Highlighting](./set_highlighting/)(HighlightingMode) | [Annotation](../annotation/) modo de resaltado. |
| [set_OnActivated](./set_onactivated/)(const System::SharedPtr\<PdfAction\>\&) | Una acción que se realizará cuando la anotación se active. |
| [set_ReadOnly](./set_readonly/)(bool) | Establece el estado de solo lectura del campo. |
| [set_Required](./set_required/)(bool) | Establece el estado requerido del campo. |
| [WidgetAnnotation](./widgetannotation/)(const System::SharedPtr\<Document\>\&) | Crear anotación (utilizado para Generator) |
## Ver también

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
