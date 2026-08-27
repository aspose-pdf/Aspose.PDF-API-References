---
title: "Matrix.Transform"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Matrix メソッド。この matrix を使用してポイントを変換します。"
type: docs
weight: 210
url: /ja/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

この行列を使用して点を変換します。

```csharp
public Point Transform(Point p)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| p | ポイント | 変換されるポイント。 |

### 戻り値

変換結果。

## 例

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### 関連項目

* class [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

この行列を使用して座標を変換します。

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| x | Double | X 座標。 |
| y | Double | Y 座標。 |
| x1 | Double& | 変換された X 座標。 |
| y1 | Double& | 変換された Y 座標。 |

## 例

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

矩形を変換します。角度が 90 * N 度でない場合、バウンディング矩形が返されます。

```csharp
public Rectangle Transform(Rectangle rect)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | 変換される Rectangle。 |

### 戻り値

変換された Rectangle。

## 例

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


