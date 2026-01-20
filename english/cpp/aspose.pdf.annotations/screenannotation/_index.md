---
title: Aspose::Pdf::Annotations::ScreenAnnotation class
linktitle: ScreenAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::ScreenAnnotation class. A screen annotation that specifies a region of a page upon which media clips may be played in C++.'
type: docs
weight: 9800
url: /cpp/aspose.pdf.annotations/screenannotation/
---
## ScreenAnnotation class


A screen annotation that specifies a region of a page upon which media clips may be played.

```cpp
class ScreenAnnotation : public Aspose::Pdf::Annotations::Annotation,
                         public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [get_Action](./get_action/)() | Gets an action to be performed when the annotation is activated. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Title](./get_title/)() override | Gets the title of the screen annotation. |
| [ScreenAnnotation](./screenannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::String) | Creates new Screen annotation on the specified page. |
| [set_Title](./set_title/)(System::String) override | Sets the title of the screen annotation. |
## See Also

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
