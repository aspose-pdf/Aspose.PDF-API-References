---
title: Aspose::Pdf::Annotations::StampAnnotation class
linktitle: StampAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::StampAnnotation class. Represents rubber stamp annotation. This type of annotation displays text or graphics intended to look as if they were stamped on the page with a rubber stamp in C++.'
type: docs
weight: 10700
url: /cpp/aspose.pdf.annotations/stampannotation/
---
## StampAnnotation class


Represents rubber stamp annotation. This type of annotation displays text or graphics intended to look as if they were stamped on the page with a rubber stamp.

```cpp
class StampAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepts [AnnotationSelector](../annotationselector/) visitor when browsing annotation collection. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Icon](./get_icon/)() | Gets icon for rubber stamp. |
| [get_Image](./get_image/)() | Gets image of the annotation. |
| [set_Icon](./set_icon/)(StampIcon) | Sets icon for rubber stamp. |
| [set_Image](./set_image/)(System::SharedPtr\<System::IO::Stream\>) | Sets image of the annotation. |
| [StampAnnotation](./stampannotation/)(System::SharedPtr\<Document\>) | Constructor. |
| [StampAnnotation](./stampannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Creates new [Stamp](../../aspose.pdf/stamp/) annotation on the specified page. |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
