---
title: Aspose::Pdf::Annotations::InkAnnotation class
linktitle: InkAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::InkAnnotation class. Represents a freehand "scribble" composed of one or more disjoint paths in C++.'
type: docs
weight: 5200
url: /cpp/aspose.pdf.annotations/inkannotation/
---
## InkAnnotation class


Represents a freehand "scribble" composed of one or more disjoint paths.

```cpp
class InkAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Updates the points in InkList, according to the matrix transform. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_CapStyle](./get_capstyle/)() | Style of ink annotation line endings. |
| [get_InkList](./get_inklist/)() | Gets list of gestures that are independent lines which are represented by [Point](../../aspose.pdf/point/)[] arrays. |
| [InkAnnotation](./inkannotation/)(System::SharedPtr\<Document\>, System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>) | Constructor for Ink annotation for Generator. |
| [InkAnnotation](./inkannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>) | Creates new Ink annotation on the specified page. |
| [set_CapStyle](./set_capstyle/)(Aspose::Pdf::Annotations::CapStyle) | Style of ink annotation line endings. |
| [set_InkList](./set_inklist/)(System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>) | Sets list of gestures that are independent lines which are represented by [Point](../../aspose.pdf/point/)[] arrays. |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
