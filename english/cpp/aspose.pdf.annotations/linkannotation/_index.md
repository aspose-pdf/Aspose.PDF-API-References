---
title: Aspose::Pdf::Annotations::LinkAnnotation class
linktitle: LinkAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::LinkAnnotation class. Represents either a hypertext link to a destination elsewhere in the document or an action to be performed in C++.'
type: docs
weight: 6000
url: /cpp/aspose.pdf.annotations/linkannotation/
---
## LinkAnnotation class


Represents either a hypertext link to a destination elsewhere in the document or an action to be performed.

```cpp
class LinkAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [get_Action](./get_action/)() | An action to be performed when the link annotation is activated. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Destination](./get_destination/)() | A destination to be displayed when the annotation is activated. |
| [get_Highlighting](./get_highlighting/)() | The visual effect to be used when the mouse button is pressed or held down inside its active area. |
| [LinkAnnotation](./linkannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Creates new Link annotation on the specified page. |
| [set_Action](./set_action/)(System::SharedPtr\<PdfAction\>) | An action to be performed when the link annotation is activated. |
| [set_Destination](./set_destination/)(System::SharedPtr\<IAppointment\>) | A destination to be displayed when the annotation is activated. |
| [set_Highlighting](./set_highlighting/)(HighlightingMode) | The visual effect to be used when the mouse button is pressed or held down inside its active area. |
## See Also

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
