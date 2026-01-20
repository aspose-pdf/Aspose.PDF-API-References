---
title: Aspose::Pdf::Annotations::WatermarkAnnotation class
linktitle: WatermarkAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::WatermarkAnnotation class. Class describes Watermark annotation object in C++.'
type: docs
weight: 11700
url: /cpp/aspose.pdf.annotations/watermarkannotation/
---
## WatermarkAnnotation class


Class describes [Watermark](../../aspose.pdf/watermark/) annotation object.

```cpp
class WatermarkAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Apply visitor for annotation. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Overrides the definition in the base class with an empty body. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets annotation type. |
| [get_FixedPrint](./get_fixedprint/)() | Fuxed print object of [Watermark](../../aspose.pdf/watermark/) annotation. |
| [get_Opacity](./get_opacity/)() const | Gets opacity of the annotation. |
| [set_Opacity](./set_opacity/)(double) | Sets opacity of the annotation. |
| [SetText](./settext/)(System::SharedPtr\<Facades::FormattedText\>) | Set text of the annotation. |
| [SetTextAndState](./settextandstate/)(System::ArrayPtr\<System::String\>, System::SharedPtr\<Text::TextState\>) | Set text of the annotation. |
| [WatermarkAnnotation](./watermarkannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Constructor for [Watermark](../../aspose.pdf/watermark/) annotation class. |
## See Also

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
