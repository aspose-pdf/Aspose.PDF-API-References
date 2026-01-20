---
title: Aspose::Pdf::Annotations::WidgetAnnotation class
linktitle: WidgetAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::WidgetAnnotation class. Class representing widget annotation in C++.'
type: docs
weight: 11800
url: /cpp/aspose.pdf.annotations/widgetannotation/
---
## WidgetAnnotation class


Class representing widget annotation.

```cpp
class WidgetAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor. |
| [get_Actions](./get_actions/)() | Gets the annotation actions. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Gets default appearance of the field. |
| [get_Exportable](./get_exportable/)() | Gets exportable flag of the field. |
| [get_Highlighting](./get_highlighting/)() | [Annotation](../annotation/) highlighting mode. |
| [get_OnActivated](./get_onactivated/)() | An action which shall be performed when the annotation is activated. |
| [get_Parent](./get_parent/)() | Gets annotation parent. |
| [get_ReadOnly](./get_readonly/)() | Gets read only status of the field. |
| [get_Required](./get_required/)() | Gets required status of the field. |
| [GetCheckedStateName](./getcheckedstatename/)() | Returns name of "checked" state according to existing state names. |
| [set_DefaultAppearance](./set_defaultappearance/)(System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>) | Sets default appearance of the field. |
| [set_Exportable](./set_exportable/)(bool) | Sets exportable flag of the field. |
| [set_Highlighting](./set_highlighting/)(HighlightingMode) | [Annotation](../annotation/) highlighting mode. |
| [set_OnActivated](./set_onactivated/)(System::SharedPtr\<PdfAction\>) | An action which shall be performed when the annotation is activated. |
| [set_ReadOnly](./set_readonly/)(bool) | Sets read only status of the field. |
| [set_Required](./set_required/)(bool) | Sets required status of the field. |
| [WidgetAnnotation](./widgetannotation/)(System::SharedPtr\<Document\>) | Create annotation (used for Generator) |
## See Also

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
