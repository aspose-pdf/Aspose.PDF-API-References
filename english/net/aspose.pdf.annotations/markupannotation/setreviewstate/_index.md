---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: MarkupAnnotation method. Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. Note the state stored in other text annotation which has state and statemodel keys
type: docs
weight: 140
url: /net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. Note, the state stored in other text annotation which has state and statemodel keys.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Status for assignment. |
| userName | String | The username that appears in the comments header. The name can be the same as the name in the Title of the target annotation or different if the status is set by another user. |

### See Also

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. The state is set by the user who created the target annotation. The value is taken from the Title property of the target annotation. Note, the state stored in other text annotation which has state and statemodel keys.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | Status for assignment. |

### See Also

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


