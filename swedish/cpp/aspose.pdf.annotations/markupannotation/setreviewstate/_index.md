---
title: "Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState metod"
linktitle: "SetReviewState"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState metod. Ställer in granskningsstatus för en annotation. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Tillståndet sätts av den användare som skapade målannotation. Värdet tas från Title‑egenskapen hos målannotation. Observera, tillståndet lagras i annan textannotation som har nycklarna state och statemodel i C++."
type: docs
weight: 2200
url: /sv/cpp/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## MarkupAnnotation::SetReviewState(AnnotationState) method


Ställer in granskningsstatus för en annotation. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Tillståndet sätts av den användare som skapade målannotation. Värdet tas från Title‑egenskapen hos målannotation. [Note](../../../aspose.pdf/note/), tillståndet lagras i annan textannotation som har nycklarna state och statemodel.

```cpp
void Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState(AnnotationState state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| state | AnnotationState | Status för tilldelning. |

## Se även

* Enum [AnnotationState](../../annotationstate/)
* Class [MarkupAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## MarkupAnnotation::SetReviewState(AnnotationState, const System::String\&) method


Ställer in granskningsstatus för en annotation. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. [Note](../../../aspose.pdf/note/), tillståndet lagras i annan textannotation som har nycklarna state och statemodel.

```cpp
void Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState(AnnotationState state, const System::String &userName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| state | AnnotationState | Status för tilldelning. |
| userName | const System::String\& | Användarnamnet som visas i kommentarhuvudet. Namnet kan vara detsamma som namnet i titeln för målannotation eller annorlunda om statusen har satts av en annan användare. |

## Se även

* Enum [AnnotationState](../../annotationstate/)
* Class [String](../../../system/string/)
* Class [MarkupAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
