---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: MarkupAnnotation 方法。设置注释的审阅状态。标记和未标记状态被忽略，因为它们不属于审阅状态模型。请注意，存储在其他文本注释中的状态，该注释具有状态和状态模型键
type: docs
weight: 140
url: /zh/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

设置注释的审阅状态。标记和未标记状态被忽略，因为它们不属于审阅状态模型。请注意，存储在其他文本注释中的状态，该注释具有状态和状态模型键。

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| state | AnnotationState | 分配的状态。 |
| userName | String | 出现在评论头中的用户名。该名称可以与目标注释的标题中的名称相同，也可以不同，如果状态是由其他用户设置的。 |

### 另请参阅

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

设置注释的审阅状态。标记和未标记状态被忽略，因为它们不属于审阅状态模型。状态由创建目标注释的用户设置。该值取自目标注释的标题属性。请注意，存储在其他文本注释中的状态，该注释具有状态和状态模型键。

```csharp
public void SetReviewState(AnnotationState state)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| state | AnnotationState | 分配的状态。 |

### 另请参阅

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)