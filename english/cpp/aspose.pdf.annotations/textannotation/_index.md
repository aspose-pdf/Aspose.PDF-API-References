---
title: Aspose::Pdf::Annotations::TextAnnotation class
linktitle: TextAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::TextAnnotation class. Represents a text annotation that is a ''sticky note'' attached to a point in the PDF document in C++.'
type: docs
weight: 11100
url: /cpp/aspose.pdf.annotations/textannotation/
---
## TextAnnotation class


Represents a text annotation that is a 'sticky note' attached to a point in the PDF document.

```cpp
class TextAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Overrides the definition in the base class with an empty body. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Icon](./get_icon/)() | Gets an icon to be used in displaying the annotation. |
| [get_Open](./get_open/)() | Gets a flag specifying whether the annotation should initially be displayed open. |
| [set_Icon](./set_icon/)(TextIcon) | Sets an icon to be used in displaying the annotation. |
| [set_Open](./set_open/)(bool) | Sets a flag specifying whether the annotation should initially be displayed open. |
| [TextAnnotation](./textannotation/)(System::SharedPtr\<Document\>) | Constructor for annotation when used in Generator. |
| [TextAnnotation](./textannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Creates new [Text](../../aspose.pdf.text/) annotation on the specified page. |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
