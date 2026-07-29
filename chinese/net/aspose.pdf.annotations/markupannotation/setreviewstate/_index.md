---
title: "MarkupAnnotation.SetReviewState"
second_title: "Aspose.PDF for .NET API 参考"
description: "MarkupAnnotation 方法。设置注释的审阅状态。已标记和未标记状态将被忽略，因为它们不属于审阅 StateModel。注意，其他具有 state 和 statemodel 键的文本注释中存储的状态"
type: docs
weight: 140
url: /zh/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

为注释设置审阅状态。已标记和未标记状态将被忽略，因为它们不属于 Review StateModel。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 状态 | AnnotationState | 分配状态。 |
| userName | String | 出现在评论标题中的用户名。该名称可以与目标注释标题中的名称相同，也可以在状态由其他用户设置时不同。 |

### 另请参见

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

为注释设置审阅状态。已标记和未标记状态将被忽略，因为它们不属于 Review StateModel。该状态由创建目标注释的用户设置，值取自目标注释的 Title 属性。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。

```csharp
public void SetReviewState(AnnotationState state)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 状态 | AnnotationState | 分配状态。 |

### 另请参见

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


