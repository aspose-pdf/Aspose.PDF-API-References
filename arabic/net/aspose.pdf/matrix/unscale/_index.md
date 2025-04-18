---
title: Matrix.UnScale
second_title: Aspose.PDF for .NET API Reference
description: طريقة المصفوفة. تعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية x = D  x1 - C  y1 / A  D - C  B؛ y = A y1 - B x1 / (A D - C B؛
type: docs
weight: 220
url: /ar/net/aspose.pdf/matrix/unscale/
---
## طريقة Matrix.UnScale

تعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية: x = (D * x1 - C * y1) / (A * D - C * B)؛ y = (A* y1 - B* x1) / (A* D - C* B)؛

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
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