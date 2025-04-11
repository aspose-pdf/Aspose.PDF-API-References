---
title: Matrix.UnScale
second_title: Aspose.PDF for .NET API Reference
description: Matrix メソッド。次の式を使用して、x1 と y1 を元に戻し、行列変換の前の x と y を返します: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);
type: docs
weight: 220
url: /ja/net/aspose.pdf/matrix/unscale/
---
## Matrix.UnScale メソッド

x1 と y1 を元に戻し、次の式を使用して行列変換の前の x と y を返します: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 | Double | 入力 X 座標 |
| y1 | Double | 入力 Y 座標 |
| x | Double& | 出力 X 座標 |
| y | Double& | 出力 Y 座標 |

### 関連項目

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)