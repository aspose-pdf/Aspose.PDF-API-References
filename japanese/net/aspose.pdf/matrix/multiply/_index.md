---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: マトリックスメソッド。マトリックスを他のマトリックスで掛け算します
type: docs
weight: 170
url: /ja/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply メソッド

マトリックスを他のマトリックスで掛け算します。

```csharp
public Matrix Multiply(Matrix other)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | Matrix | 掛け算するマトリックス。 |

### 戻り値

掛け算の結果。

## 例

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### 参照

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)