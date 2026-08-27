---
title: "Matrix.UnScale"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Matrix. تُعيد تحجيم x1 و y1 وتُعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية x  D  x1  C  y1 / A  D  C  B y  A y1  B x1 / A D  C B"
type: docs
weight: 220
url: /ar/net/aspose.pdf/matrix/unscale/
---
## Matrix.UnScale method

يعيد تحجيم x1 و y1 ويعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C * B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
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


