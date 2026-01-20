---
title: Aspose::Pdf::Annotations::CaretAnnotation class
linktitle: CaretAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::CaretAnnotation class. Class representing Caret annotation in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf.annotations/caretannotation/
---
## CaretAnnotation class


Class representing Caret annotation.

```cpp
class CaretAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [CaretAnnotation](./caretannotation/)(System::SharedPtr\<Document\>) | Constructor for usign in Generator. |
| [CaretAnnotation](./caretannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Creates new Caret annotation on the specified page. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Frame](./get_frame/)() | Gets caret rectangle. |
| [get_Symbol](./get_symbol/)() | Gets symbol associated with caret. |
| [set_Frame](./set_frame/)(System::SharedPtr\<Rectangle\>) | Sets caret rectangle. |
| [set_Symbol](./set_symbol/)(CaretSymbol) | Sets symbol associated with caret. |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
