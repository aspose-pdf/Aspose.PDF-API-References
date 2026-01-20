---
title: Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState method
linktitle: SetReviewState
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState method. Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. The state is set by the user who created the target annotation. The value is taken from the Title property of the target annotation. Note, the state stored in other text annotation which has state and statemodel keys in C++.'
type: docs
weight: 2200
url: /cpp/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## MarkupAnnotation::SetReviewState(AnnotationState) method


Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. The state is set by the user who created the target annotation. The value is taken from the Title property of the target annotation. [Note](../../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys.

```cpp
void Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState(AnnotationState state)
```


| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Status for assignment. |

## See Also

* Enum [AnnotationState](../../annotationstate/)
* Class [MarkupAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## MarkupAnnotation::SetReviewState(AnnotationState, System::String) method


Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. [Note](../../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys.

```cpp
void Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState(AnnotationState state, System::String userName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Status for assignment. |
| userName | System::String | The username that appears in the comments header. The name can be the same as the name in the Title of the target annotation or different if the status is set by another user. |

## See Also

* Enum [AnnotationState](../../annotationstate/)
* Class [String](../../../system/string/)
* Class [MarkupAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
