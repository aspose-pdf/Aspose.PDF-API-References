---
title: "MarkupAnnotation.SetReviewState"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة MarkupAnnotation. تحدد حالة المراجعة للتعليق التوضيحي. يتم تجاهل الحالات Marked و Unmarked لأنها لا تنتمي إلى نموذج حالة المراجعة Review StateModel. لاحظ الحالة المخزنة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel"
type: docs
weight: 140
url: /ar/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

يضبط حالة المراجعة لتعليق. يتم تجاهل حالات 'محدد' و'غير محدد' لأنها لا تنتمي إلى نموذج حالة المراجعة (Review StateModel). ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| state | AnnotationState | الحالة للتعيين. |
| userName | String | اسم المستخدم الذي يظهر في رأس التعليقات. يمكن أن يكون الاسم هو نفسه الاسم الموجود في عنوان التعليق التوضيحي المستهدف أو مختلفًا إذا تم تعيين الحالة بواسطة مستخدم آخر. |

### انظر أيضًا

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

يضبط حالة المراجعة لتعليق. يتم تجاهل حالات 'محدد' و'غير محدد' لأنها لا تنتمي إلى نموذج حالة المراجعة (Review StateModel). يتم تعيين الحالة من قبل المستخدم الذي أنشأ التعليق المستهدف. يتم أخذ القيمة من خاصية Title للتعليق المستهدف. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel.

```csharp
public void SetReviewState(AnnotationState state)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| state | AnnotationState | الحالة للتعيين. |

### انظر أيضًا

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


