---
title: Matrix.Skew
second_title: Aspose.PDF for .NET API Reference
description: マトリックスメソッド。指定された回転角度のマトリックスを作成します
type: docs
weight: 30
url: /ja/net/aspose.pdf/matrix/skew/
---
## Matrix.Skew メソッド

指定された回転角度のマトリックスを作成します。

```csharp
public static Matrix Skew(double alpha, double beta)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alpha | Double | ラジアンでのスキュー x 角度。 |
| beta | Double | ラジアンでのスキュー y 角度。 |

### 戻り値

変換マトリックス。

## 例

```csharp
Matrix m = Matrix.Skew(Math.PI / 2, Math.PI / 2);
```

### 関連項目

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)