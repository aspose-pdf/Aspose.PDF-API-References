---
title: "Aspose::Pdf::Annotations::MarkupAnnotation-klass"
linktitle: "MarkupAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::MarkupAnnotation-klass. Abstrakt klass som representerar markup-annotation i C++."
type: docs
weight: 6100
url: /sv/cpp/aspose.pdf.annotations/markupannotation/
---
## MarkupAnnotation class


Abstrakt klass som representerar markup‑anteckning.

```cpp
class MarkupAnnotation : public Aspose::Pdf::Annotations::Annotation,
                         public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ClearState](./clearstate/)() | Rensar tillstånd och tillståndsmodell för annotationen. Till exempel rensar den granskningsstatusen för en annotation. [Note](../../aspose.pdf/note/), tillståndet som lagras i annan textannotation som har nycklarna state och statemodel. |
| [get_CreationDate](./get_creationdate/)() | Hämtar datum och tid då annotationen skapades. |
| [get_InReplyTo](./get_inreplyto/)() | En referens till den annotation som denna annotation är \"in reply to\". Båda annotationerna måste vara på samma sida i dokumentet. |
| [get_Opacity](./get_opacity/)() | Hämtar det konstanta opacitetsvärdet som ska användas vid målning av annotationen. |
| [get_Popup](./get_popup/)() | Popup-annotation för att ange eller redigera texten som är associerad med denna annotation. |
| [get_ReplyType](./get_replytype/)() | En sträng som specificerar förhållandet (\"reply type\") mellan denna annotation och den som anges av InReplyTo. |
| [get_RichText](./get_richtext/)() | Hämtar en rich text-sträng som ska visas i popup-fönstret när annotationen öppnas. |
| [get_Subject](./get_subject/)() | Hämtar text som representerar en beskrivning av objektet. |
| [get_Title](./get_title/)() override | Hämtar en textetikett som ska visas i titelraden på annotationens popup-fönster när den är öppen och aktiv. Detta fält ska identifiera användaren som lade till annotationen. |
| [GetState](./getstate/)() | Hämtar tillståndet för annotationen. [Note](../../aspose.pdf/note/), tillståndet som lagras i annan textannotation som har nycklarna state och statemodel. |
| [GetStateModel](./getstatemodel/)() | Hämtar tillståndsmodellen för annoteringen. [Note](../../aspose.pdf/note/), tillståndet lagras i annan textannotering som har nycklarna state och statemodel. |
| [MarkupAnnotation](./markupannotation/)(const System::SharedPtr\<Document\>\&) | Konstruktor för markup-annotering. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | Hämtar datum och tid då annotationen skapades. |
| [set_InReplyTo](./set_inreplyto/)(const System::SharedPtr\<Annotation\>\&) | En referens till den annotation som denna annotation är \"in reply to\". Båda annotationerna måste vara på samma sida i dokumentet. |
| [set_Opacity](./set_opacity/)(double) | Ställer in det konstanta opacitetsvärdet som ska användas vid målning av annoteringen. |
| [set_Popup](./set_popup/)(const System::SharedPtr\<PopupAnnotation\>\&) | Popup-annotation för att ange eller redigera texten som är associerad med denna annotation. |
| [set_ReplyType](./set_replytype/)(Aspose::Pdf::Annotations::ReplyType) | En sträng som specificerar förhållandet (\"reply type\") mellan denna annotation och den som anges av InReplyTo. |
| [set_RichText](./set_richtext/)(const System::String\&) | Ställer in en rich text-sträng som ska visas i popup-fönstret när annoteringen öppnas. |
| [set_Subject](./set_subject/)(const System::String\&) | Hämtar text som representerar en beskrivning av objektet. |
| [set_Title](./set_title/)(System::String) override | Ställer in en textetikett som ska visas i titelraden på annoteringens popup-fönster när den är öppen och aktiv. Denna post ska identifiera användaren som lade till annoteringen. |
| [SetMarkedState](./setmarkedstate/)(bool) | Ställer in markerat och omarkerat tillstånd för annoteringen. [Note](../../aspose.pdf/note/), tillståndet lagras i annan textannotering som har nycklarna state och statemodel. |
| [SetReviewState](./setreviewstate/)(AnnotationState, const System::String\&) | Ställer in granskningsstatus för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. [Note](../../aspose.pdf/note/), tillståndet lagras i annan textannotering som har nycklarna state och statemodel. |
| [SetReviewState](./setreviewstate/)(AnnotationState) | Ställer in granskningsstatus för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Tillståndet sätts av användaren som skapade målannoteringen. Värdet hämtas från Title‑egenskapen för målannoteringen. [Note](../../aspose.pdf/note/), tillståndet lagras i annan textannotering som har nycklarna state och statemodel. |
## Se även

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
