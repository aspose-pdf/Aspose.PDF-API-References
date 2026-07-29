---
title: "Matrix.Scale"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Matrix. تقوم بتكبير x و y باستخدام المصفوفة وفق الصيغة التالية x1  Ax  Cy y1  Bx  Dy"
type: docs
weight: 190
url: /ar/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

يقوم بتحجيم x و y باستخدام المصفوفة وفق الصيغة التالية: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| x | Double | إحداثي X الإدخال |
| y | Double | إحداثي Y الإدخال |
| x1 | Double& | إحداثي X الإخراج |
| y1 | Double& | إحداثي Y الإخراج |

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

يطبق التحجيم على المصفوفة المعطاة.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| sx | Double | عامل التكبير لمحور X. |
| sy | Double | عامل التكبير لمحور Y. |
| المصدر | Matrix | المصفوفة المراد تكبيرها. |

### قيمة الإرجاع

مصفوفة جديدة هي نتيجة تكبير المصفوفة المصدر.

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


