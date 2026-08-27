---
title: "Matrix.UnTransform"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Matrix メソッド。x1 と y1 を元に戻し、次の式を使用して行列変換前の x と y を返します x  D  x1  C  y1  C  F / A  D  C  B y  A  y1  B  x1  B  E / A  D  C  B"
type: docs
weight: 230
url: /ja/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform method

次の式を使用して x1 と y1 を逆変換し、行列変換前の x と y を返します: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B)。

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| x1 | Double | 入力 X 座標 |
| y1 | Double | 入力 Y 座標 |
| x | Double& | X座標の出力 |
| y | Double& | Y座標の出力 |

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


