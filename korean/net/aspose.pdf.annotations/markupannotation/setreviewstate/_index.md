---
title: "MarkupAnnotation.SetReviewState"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "MarkupAnnotation 메서드. 주석의 검토 상태를 설정합니다. Marked 및 Unmarked 상태는 Review StateModel에 속하지 않으므로 무시됩니다. 상태와 statemodel 키를 가진 다른 텍스트 주석에 저장된 상태를 참고하십시오."
type: docs
weight: 140
url: /ko/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

주석의 검토 상태를 설정합니다. Marked 및 Unmarked 상태는 Review StateModel에 속하지 않으므로 무시됩니다. 참고: state 및 statemodel 키를 가진 다른 텍스트 주석에 저장된 상태는 그대로 유지됩니다.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 상태 | AnnotationState | 할당을 위한 상태. |
| userName | String | 댓글 헤더에 표시되는 사용자 이름입니다. 이 이름은 대상 주석의 Title에 있는 이름과 동일할 수도 있고, 상태가 다른 사용자에 의해 설정된 경우에는 다를 수도 있습니다. |

### 또 보기

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

주석의 검토 상태를 설정합니다. Marked 및 Unmarked 상태는 Review StateModel에 속하지 않으므로 무시됩니다. 상태는 대상 주석을 만든 사용자가 설정하며, 값은 대상 주석의 Title 속성에서 가져옵니다. 참고: state 및 statemodel 키를 가진 다른 텍스트 주석에 저장된 상태는 그대로 유지됩니다.

```csharp
public void SetReviewState(AnnotationState state)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 상태 | AnnotationState | 할당을 위한 상태. |

### 또 보기

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


