---
title: "Matrix.Multiply"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Matrix メソッド。matrix を他の matrix と乗算します。"
type: docs
weight: 170
url: /ja/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply method

行列を他の行列で乗算します。

```csharp
public Matrix Multiply(Matrix other)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 他 | Matrix | 乗算行列。 |

### 戻り値

乗算の結果。

## 例

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


