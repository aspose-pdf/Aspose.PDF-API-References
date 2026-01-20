---
title: Aspose::Pdf::Annotations::TextMarkupAnnotation class
linktitle: TextMarkupAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::TextMarkupAnnotation class. Abstract base class for text markup annotations in C++.'
type: docs
weight: 11300
url: /cpp/aspose.pdf.annotations/textmarkupannotation/
---
## TextMarkupAnnotation class


Abstract base class for text markup annotations.

```cpp
class TextMarkupAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Updates the QuadPoints, according to the matrix transform. |
| [get_QuadPoints](./get_quadpoints/)() | Gets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation. |
| [GetMarkedText](./getmarkedtext/)() | Gets text under markup annotation as string. |
| [GetMarkedTextFragments](./getmarkedtextfragments/)() | Gets text under markup annotation as [TextFragmentCollection](../). |
| [set_QuadPoints](./set_quadpoints/)(System::ArrayPtr\<System::SharedPtr\<Point\>\>) | Sets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation. |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
