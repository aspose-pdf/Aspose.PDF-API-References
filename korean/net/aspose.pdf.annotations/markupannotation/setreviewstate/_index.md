---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: MarkupAnnotation 메서드. 주석에 대한 검토 상태를 설정합니다. Marked 및 Unmarked 상태는 Review StateModel에 속하지 않으므로 무시됩니다. 상태 및 statemodel 키가 있는 다른 텍스트 주석에 저장된 상태를 참고하십시오.
type: docs
weight: 140
url: /ko/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

주석에 대한 검토 상태를 설정합니다. Marked 및 Unmarked 상태는 Review StateModel에 속하지 않으므로 무시됩니다. 상태 및 statemodel 키가 있는 다른 텍스트 주석에 저장된 상태를 참고하십시오.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | 할당을 위한 상태입니다. |
| userName | String | 댓글 헤더에 나타나는 사용자 이름입니다. 이름은 대상 주석의 제목에 있는 이름과 같거나, 다른 사용자가 상태를 설정한 경우 다를 수 있습니다. |

### See Also

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

주석에 대한 검토 상태를 설정합니다. Marked 및 Unmarked 상태는 Review StateModel에 속하지 않으므로 무시됩니다. 상태는 대상 주석을 생성한 사용자가 설정합니다. 값은 대상 주석의 Title 속성에서 가져옵니다. 상태 및 statemodel 키가 있는 다른 텍스트 주석에 저장된 상태를 참고하십시오.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | 할당을 위한 상태입니다. |

### See Also

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)