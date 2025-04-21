---
title: Matrix.UnTransform
second_title: Aspose.PDF for .NET API Reference
description: طريقة المصفوفة. تعيد تحويل x1 و y1 وتعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية x = D  x1 - C  y1 + C  F / A  D - C  B ؛ y = A  y1 - B  x1 + B  E / A  D - C  B.
type: docs
weight: 230
url: /ar/net/aspose.pdf/matrix/untransform/
---
## طريقة Matrix.UnTransform

تعيد تحويل x1 و y1 وتعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x1 | Double | إحداثي X المدخل |
| y1 | Double | إحداثي Y المدخل |
| x | Double& | إحداثي X الناتج |
| y | Double& | إحداثي Y الناتج |

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)