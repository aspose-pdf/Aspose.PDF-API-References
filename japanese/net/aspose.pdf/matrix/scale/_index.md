---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: マトリックスメソッド。次の式を使用して、マトリックスで x と y をスケーリングします x1 = Ax + Cy; y1 = Bx + Dy
type: docs
weight: 190
url: /ja/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

次の式を使用して、マトリックスで x と y をスケーリングします: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | Double | 入力 X 座標 |
| y | Double | 入力 Y 座標 |
| x1 | Double& | 出力 X 座標 |
| y1 | Double& | 出力 Y 座標 |

### 参照

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

指定されたマトリックスにスケーリングを適用します。

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sx | Double | X 軸のスケーリング係数。 |
| sy | Double | Y 軸のスケーリング係数。 |
| source | Matrix | スケーリングするマトリックス。 |

### 戻り値

ソースマトリックスのスケーリング結果としての新しいマトリックス。

### 参照

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)