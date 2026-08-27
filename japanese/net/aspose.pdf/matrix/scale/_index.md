---
title: "Matrix.Scale"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Matrix メソッド。次の式を使用して x と y を行列でスケーリングします x1  Ax  Cy y1  Bx  Dy"
type: docs
weight: 190
url: /ja/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

次の式を使用して行列で x と y をスケーリングします: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| x | Double | 入力 X 座標 |
| y | Double | 入力 Y 座標 |
| x1 | Double& | X座標の出力 |
| y1 | Double& | Y座標の出力 |

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

指定された Matrix にスケーリングを適用します。

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| sx | Double | X 軸のスケーリング係数です。 |
| sy | Double | Y 軸のスケーリング係数です。 |
| source | Matrix | スケーリング対象の行列です。 |

### 戻り値

ソース行列をスケーリングした結果得られる新しい行列です。

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


