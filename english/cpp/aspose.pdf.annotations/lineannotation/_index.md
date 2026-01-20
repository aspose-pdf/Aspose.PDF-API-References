---
title: Aspose::Pdf::Annotations::LineAnnotation class
linktitle: LineAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::LineAnnotation class. Class representing line annotation in C++.'
type: docs
weight: 5700
url: /cpp/aspose.pdf.annotations/lineannotation/
---
## LineAnnotation class


Class representing line annotation.

```cpp
class LineAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor to annotation processing. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Updates the Starting and Ending points, according to the matrix transform. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_CaptionOffset](./get_captionoffset/)() | Gets caption text offset from its normal position. |
| [get_CaptionPosition](./get_captionposition/)() | Gets annotation caption position. |
| [get_Ending](./get_ending/)() | Gets line ending point. |
| [get_EndingStyle](./get_endingstyle/)() | Gets ending style for end point of line. |
| [get_Intent](./get_intent/)() | Gets the intent of the line annotation. |
| [get_InteriorColor](./get_interiorcolor/)() | Gets interior color of the annotation. |
| [get_LeaderLine](./get_leaderline/)() | Gets leader line length. |
| [get_LeaderLineExtension](./get_leaderlineextension/)() | Gets length of leader line extension. |
| [get_LeaderLineOffset](./get_leaderlineoffset/)() | Gets leader line offset. |
| [get_Measure](./get_measure/)() | [Measure](../measure/) units specifed for this annotation. |
| [get_ShowCaption](./get_showcaption/)() | Gets boolean flag which determinies is contents must be shown as caption. |
| [get_Starting](./get_starting/)() | Gets starting point of line. |
| [get_StartingStyle](./get_startingstyle/)() | Gets line ending style for line starting point. |
| [LineAnnotation](./lineannotation/)(System::SharedPtr\<Document\>, System::SharedPtr\<Point\>, System::SharedPtr\<Point\>) | Constructor for using with Generator. |
| [LineAnnotation](./lineannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::SharedPtr\<Point\>, System::SharedPtr\<Point\>) | Creates new Line annotation on the specified page. |
| [set_CaptionOffset](./set_captionoffset/)(System::SharedPtr\<Point\>) | Sets caption text offset from its normal position. |
| [set_CaptionPosition](./set_captionposition/)(Aspose::Pdf::Annotations::CaptionPosition) | Sets annotation caption position. |
| [set_Ending](./set_ending/)(System::SharedPtr\<Point\>) | Sets line ending point. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Sets ending style for end point of line. |
| [set_Intent](./set_intent/)(LineIntent) | Sets the intent of the line annotation. |
| [set_InteriorColor](./set_interiorcolor/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets interior color of the annotation. |
| [set_LeaderLine](./set_leaderline/)(double) | Sets leader line length. |
| [set_LeaderLineExtension](./set_leaderlineextension/)(double) | Sets length of leader line extension. |
| [set_LeaderLineOffset](./set_leaderlineoffset/)(double) | Sets leader line offset. |
| [set_Measure](./set_measure/)(System::SharedPtr\<Aspose::Pdf::Annotations::Measure\>) | [Measure](../measure/) units specifed for this annotation. |
| [set_ShowCaption](./set_showcaption/)(bool) | Sets boolean flag which determinies is contents must be shown as caption. |
| [set_Starting](./set_starting/)(System::SharedPtr\<Point\>) | Sets starting point of line. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Sets line ending style for line starting point. |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
