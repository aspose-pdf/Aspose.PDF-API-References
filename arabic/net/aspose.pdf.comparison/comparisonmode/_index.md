---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonMode enum. تعداد وضعيات المقارنة
type: docs
weight: 3140
url: /ar/net/aspose.pdf.comparison/comparisonmode/
---
## تعداد وضعيات المقارنة

تعداد وضعيات المقارنة.

```csharp
public enum ComparisonMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Normal | `0` | وضع عادي. يتم أخذ المسافات داخل أجزاء النص في الاعتبار فقط (اعتمادًا على طريقة إنشاء الوثيقة.) |
| IgnoreSpaces | `1` | يتم تجاهل جميع المسافات. يتم البحث عن التغييرات فقط في الكلمات. |
| ParseSpaces | `2` | الوضع مشابه للوضع العادي، ولكنه يحاول أخذ المسافات البصرية بين أجزاء النص في الاعتبار بناءً على المسافة. قد لا يكون التعرف على عدد المسافات بين الأجزاء دقيقًا لأن ذلك يعتمد بشكل كبير على كيفية إنشاء الوثائق. إذا تم إنشاء الوثائق بواسطة مولدات مختلفة، فقد تكون هناك عدم دقة في مقارنة المسافات بين أجزاء النص. |

### انظر أيضًا

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)