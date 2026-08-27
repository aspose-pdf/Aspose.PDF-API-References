---
title: "Matrix.Transform"
second_title: "Aspose.PDF for .NET API 参考"
description: "Matrix 方法。使用此矩阵转换点。"
type: docs
weight: 210
url: /zh/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

使用此矩阵转换点。

```csharp
public Point Transform(Point p)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | 点 | 将被转换的 Point。 |

### 返回值

转换结果。

## 示例

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### 另请参见

* class [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

使用此矩阵转换坐标。

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | X 坐标。 |
| y | Double | Y 坐标。 |
| x1 | Double& | 已转换的 X 坐标。 |
| y1 | Double& | 已转换的 Y 坐标。 |

## 示例

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

转换矩形。如果角度不是 90 * N 度，则返回外接矩形。

```csharp
public Rectangle Transform(Rectangle rect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 要转换的 Rectangle。 |

### 返回值

已转换的 Rectangle。

## 示例

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### 另请参见

* class [Rectangle](../../rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


