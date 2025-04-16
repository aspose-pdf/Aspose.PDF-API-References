---
title: Matrix.UnTransform
second_title: Aspose.PDF for .NET API Reference
description: マトリックスメソッド。次の式を使用して、x1 と y1 を元に戻し、マトリックス変換前の x と y を返します: x = （D * x1 - C * y1 + C * F） / （A * D - C * B）; y = （A * y1 - B * x1 + B * E） / （A * D - C * B）。
type: docs
weight: 230
url: /ja/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform メソッド

x1 と y1 を元に戻し、次の式を使用してマトリックス変換前の x と y を返します: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B)。

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 | Double | 入力 X 座標 |
| y1 | Double | 入力 Y 座標 |
| x | Double& | 出力 X 座標 |
| y | Double& | 出力 Y 座標 |

### 参照

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)