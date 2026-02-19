---
title: Aspose::Pdf::Annotations::MarkupAnnotation class
linktitle: MarkupAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::MarkupAnnotation class. Abstract class representing markup annotation in C++.'
type: docs
weight: 6100
url: /cpp/aspose.pdf.annotations/markupannotation/
---
## MarkupAnnotation class


Abstract class representing markup annotation.

```cpp
class MarkupAnnotation : public Aspose::Pdf::Annotations::Annotation,
                         public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [ClearState](./clearstate/)() | Clears state and state model for the annotation. For example, clears the review status for an annotation. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
| [get_CreationDate](./get_creationdate/)() | Gets date and time when annotation was created. |
| [get_InReplyTo](./get_inreplyto/)() | A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document. |
| [get_Opacity](./get_opacity/)() | Gets the constant opacity value to be used in painting the annotation. |
| [get_Popup](./get_popup/)() | Pop-up annotation for entering or editing the text associated with this annotation. |
| [get_ReplyType](./get_replytype/)() | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [get_RichText](./get_richtext/)() | Gets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [get_Subject](./get_subject/)() | Gets text representing desciption of the object. |
| [get_Title](./get_title/)() override | Gets a text label that shall be displayed in the title bar of the annotation�s popup window when open and active. This entry shall identify the user who added the annotation. |
| [GetState](./getstate/)() | Gets the state of the annotation. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
| [GetStateModel](./getstatemodel/)() | Gets the state model of the annotation. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
| [MarkupAnnotation](./markupannotation/)(System::SharedPtr\<Document\>) | Constructor for markup annotation. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | Gets date and time when annotation was created. |
| [set_InReplyTo](./set_inreplyto/)(System::SharedPtr\<Annotation\>) | A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document. |
| [set_Opacity](./set_opacity/)(double) | Sets the constant opacity value to be used in painting the annotation. |
| [set_Popup](./set_popup/)(System::SharedPtr\<PopupAnnotation\>) | Pop-up annotation for entering or editing the text associated with this annotation. |
| [set_ReplyType](./set_replytype/)(Aspose::Pdf::Annotations::ReplyType) | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [set_RichText](./set_richtext/)(System::String) | Sets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [set_Subject](./set_subject/)(System::String) | Gets text representing desciption of the object. |
| [set_Title](./set_title/)(System::String) override | Sets a text label that shall be displayed in the title bar of the annotation�s popup window when open and active. This entry shall identify the user who added the annotation. |
| [SetMarkedState](./setmarkedstate/)(bool) | Sets Marked and Unmarked state for the annotation. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
| [SetReviewState](./setreviewstate/)(AnnotationState, System::String) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
| [SetReviewState](./setreviewstate/)(AnnotationState) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. The state is set by the user who created the target annotation. The value is taken from the Title property of the target annotation. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
## See Also

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
