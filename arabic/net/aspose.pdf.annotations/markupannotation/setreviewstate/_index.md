---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: طريقة MarkupAnnotation. تعيين حالة المراجعة للتعليق. يتم تجاهل حالات "محدد" و"غير محدد" لأنها لا تنتمي إلى نموذج حالة المراجعة. لاحظ الحالة المخزنة في تعليق نصي آخر يحتوي على مفاتيح الحالة ونموذج الحالة
type: docs
weight: 140
url: /ar/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

تعيين حالة المراجعة للتعليق. يتم تجاهل حالات "محدد" و"غير محدد" لأنها لا تنتمي إلى نموذج حالة المراجعة. لاحظ، الحالة المخزنة في تعليق نصي آخر يحتوي على مفاتيح الحالة ونموذج الحالة.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | الحالة للتعيين. |
| userName | String | اسم المستخدم الذي يظهر في رأس التعليقات. يمكن أن يكون الاسم هو نفسه الاسم في عنوان التعليق المستهدف أو مختلفًا إذا تم تعيين الحالة بواسطة مستخدم آخر. |

### See Also

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

تعيين حالة المراجعة للتعليق. يتم تجاهل حالات "محدد" و"غير محدد" لأنها لا تنتمي إلى نموذج حالة المراجعة. يتم تعيين الحالة بواسطة المستخدم الذي أنشأ التعليق المستهدف. يتم أخذ القيمة من خاصية العنوان للتعليق المستهدف. لاحظ، الحالة المخزنة في تعليق نصي آخر يحتوي على مفاتيح الحالة ونموذج الحالة.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | AnnotationState | الحالة للتعيين. |

### See Also

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)