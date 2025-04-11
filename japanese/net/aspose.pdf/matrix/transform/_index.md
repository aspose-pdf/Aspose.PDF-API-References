---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: マトリックスメソッド。このマトリックスを使用してポイントを変換します
type: docs
weight: 210
url: /ja/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

このマトリックスを使用してポイントを変換します。

```csharp
public Point Transform(Point p)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| p | Point | 変換されるポイント。 |

### 戻り値

変換結果。

## 例

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### 参照

* クラス [Point](../../point/)
* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

このマトリックスを使用して座標を変換します。

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | Double | X座標。 |
| y | Double | Y座標。 |
| x1 | Double& | 変換されたX座標。 |
| y1 | Double& | 変換されたY座標。 |

## 例

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### 参照

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

矩形を変換します。角度が90 * N度でない場合、バウンディング矩形が返されます。

```csharp
public Rectangle Transform(Rectangle rect)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | 変換される矩形。 |

### 戻り値

変換された矩形。

## 例

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### 参照

* クラス [Rectangle](../../rectangle/)
* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)