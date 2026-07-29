---
title: "Matrix.Transform"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Matrix. يحول النقطة باستخدام هذه المصفوفة"
type: docs
weight: 210
url: /ar/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

يحوّل النقطة باستخدام هذه المصفوفة.

```csharp
public Point Transform(Point p)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| p | نقطة | النقطة التي سيتم تحويلها. |

### قيمة الإرجاع

نتيجة التحويل.

## أمثلة

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### انظر أيضًا

* class [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

يحوّل الإحداثيات باستخدام هذه المصفوفة.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| x | Double | الإحداثي X. |
| y | Double | الإحداثي Y. |
| x1 | Double& | الإحداثي X المحول. |
| y1 | Double& | الإحداثي Y المحول. |

## أمثلة

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

يحوّل المستطيل. إذا لم يكن الزاوية 90 * N درجة فسيتم إرجاع المستطيل المحيط.

```csharp
public Rectangle Transform(Rectangle rect)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل الذي سيتم تحويله. |

### قيمة الإرجاع

المستطيل المحول.

## أمثلة

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


