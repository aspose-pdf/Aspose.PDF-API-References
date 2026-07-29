---
title: "Matrix.UnTransform"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Matrix. تعيد تحويل x1 و y1 وتعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية x  D  x1  C  y1  C  F / A  D  C  B y  A  y1  B  x1  B  E / A  D  C  B"
type: docs
weight: 230
url: /ar/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform method

يعيد تحويل x1 و y1 ويعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| x1 | Double | إحداثي X الإدخال |
| y1 | Double | إحداثي Y الإدخال |
| x | Double& | إحداثي X الإخراج |
| y | Double& | إحداثي Y الإخراج |

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


