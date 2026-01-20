---
title: Aspose::Pdf::Annotations::PopupAnnotation class
linktitle: PopupAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PopupAnnotation class. Represents the pop-up annotation that displays text in a pop-up window for entry and editing in C++.'
type: docs
weight: 8800
url: /cpp/aspose.pdf.annotations/popupannotation/
---
## PopupAnnotation class


Represents the pop-up annotation that displays text in a pop-up window for entry and editing.

```cpp
class PopupAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Open](./get_open/)() | Gets a flag specifying whether the pop-up annotation should initially be displayed open. |
| [get_Parent](./get_parent/)() | Gets the parent annotation with which this pop-up annotation shall be associated. If this entry is present, the parent annotation's Contents, M, C, and T entries shall override those of the pop-up annotation itself. |
| [PopupAnnotation](./popupannotation/)(System::SharedPtr\<Document\>) | Constructor. for using in Generator. |
| [PopupAnnotation](./popupannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Creates new Popup annotation on the specified page. |
| [set_Open](./set_open/)(bool) | Sets a flag specifying whether the pop-up annotation should initially be displayed open. |
| [set_Parent](./set_parent/)(System::SharedPtr\<Annotation\>) | Sets the parent annotation with which this pop-up annotation shall be associated. If this entry is present, the parent annotation's Contents, M, C, and T entries shall override those of the pop-up annotation itself. |
## See Also

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
