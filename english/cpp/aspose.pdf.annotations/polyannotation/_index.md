---
title: Aspose::Pdf::Annotations::PolyAnnotation class
linktitle: PolyAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PolyAnnotation class. Abstract base class for poly- annotations in C++.'
type: docs
weight: 8400
url: /cpp/aspose.pdf.annotations/polyannotation/
---
## PolyAnnotation class


Abstract base class for poly- annotations.

```cpp
class PolyAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Updates the points in Vertices, according to the matrix transform. |
| [get_EndingStyle](./get_endingstyle/)() | Gets the style of second line ending. |
| [get_Intent](./get_intent/)() | Gets the intent of the polygon or polyline annotation. |
| [get_InteriorColor](./get_interiorcolor/)() | Gets the interior color with which to fill the annotation's line endings. |
| [get_Measure](./get_measure/)() | [Measure](../measure/) units specifed for this annotation. |
| [get_StartingStyle](./get_startingstyle/)() | Gets the style of first line ending. |
| [get_Vertices](./get_vertices/)() | Gets an array of points representing the horizontal and vertical coordinates of each vertex. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Sets the style of second line ending. |
| [set_Intent](./set_intent/)(PolyIntent) | Sets the intent of the polygon or polyline annotation. |
| [set_InteriorColor](./set_interiorcolor/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets the interior color with which to fill the annotation's line endings. |
| [set_Measure](./set_measure/)(System::SharedPtr\<Aspose::Pdf::Annotations::Measure\>) | [Measure](../measure/) units specifed for this annotation. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Sets the style of first line ending. |
| [set_Vertices](./set_vertices/)(System::ArrayPtr\<System::SharedPtr\<Point\>\>) | Sets an array of points representing the horizontal and vertical coordinates of each vertex. |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
