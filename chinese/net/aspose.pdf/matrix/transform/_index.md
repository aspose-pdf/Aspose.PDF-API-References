---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: 矩阵方法。使用此矩阵变换点
type: docs
weight: 210
url: /zh/net/aspose.pdf/matrix/transform/
---
## 变换(点) {#transform}

使用此矩阵变换点。

```csharp
public Point Transform(Point p)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | 点 | 将被变换的点。 |

### 返回值

变换结果。

## 示例

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### 另见

* 类 [点](../../point/)
* 类 [矩阵](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)

---

## 变换(双精度, 双精度, out 双精度, out 双精度) {#transform_2}

使用此矩阵变换坐标。

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 双精度 | X 坐标。 |
| y | 双精度 | Y 坐标。 |
| x1 | 双精度& | 变换后的 X 坐标。 |
| y1 | 双精度& | 变换后的 Y 坐标。 |

## 示例

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### 另见

* 类 [矩阵](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)

---

## 变换(矩形) {#transform_1}

变换矩形。如果角度不是 90 * N 度，则返回边界矩形。

```csharp
public Rectangle Transform(Rectangle rect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | 矩形 | 要变换的矩形。 |

### 返回值

变换后的矩形。

## 示例

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### 另见

* 类 [矩形](../../rectangle/)
* 类 [矩阵](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)