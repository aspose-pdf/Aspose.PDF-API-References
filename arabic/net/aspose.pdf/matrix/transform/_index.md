---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: طريقة المصفوفة. تحول النقطة باستخدام هذه المصفوفة
type: docs
weight: 210
url: /ar/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

تحول النقطة باستخدام هذه المصفوفة.

```csharp
public Point Transform(Point p)
```

| Parameter | Type | Description |
| --- | --- | --- |
| p | Point | النقطة التي سيتم تحويلها. |

### Return Value

نتيجة التحويل.

## Examples

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### See Also

* class [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

تحول الإحداثيات باستخدام هذه المصفوفة.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parameter | Type | Description |
| --- | --- | --- |
| x | Double | إحداثي X. |
| y | Double | إحداثي Y. |
| x1 | Double& | إحداثي X المحول. |
| y1 | Double& | إحداثي Y المحول. |

## Examples

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### See Also

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

تحول المستطيل. إذا لم يكن الزاوية 90 * N درجة، فسيتم إرجاع المستطيل المحيط.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل الذي سيتم تحويله. |

### Return Value

المستطيل المحول.

## Examples

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### See Also

* class [Rectangle](../../rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)