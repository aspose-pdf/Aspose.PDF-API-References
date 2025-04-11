---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: طريقة المصفوفة. تقوم بتغيير حجم x و y باستخدام المصفوفة باستخدام الصيغة التالية x1  Ax  Cy y1  Bx  Dy
type: docs
weight: 190
url: /ar/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

تقوم بتغيير حجم x و y باستخدام المصفوفة باستخدام الصيغة التالية: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parameter | Type | Description |
| --- | --- | --- |
| x | Double | إحداثي X المدخل |
| y | Double | إحداثي Y المدخل |
| x1 | Double& | إحداثي X الناتج |
| y1 | Double& | إحداثي Y الناتج |

### See Also

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

تطبق تغيير الحجم على المصفوفة المعطاة.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sx | Double | عامل تغيير الحجم لمحور X. |
| sy | Double | عامل تغيير الحجم لمحور Y. |
| source | Matrix | المصفوفة التي سيتم تغيير حجمها. |

### Return Value

مصفوفة جديدة هي نتيجة تغيير حجم المصفوفة المصدر.

### See Also

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)