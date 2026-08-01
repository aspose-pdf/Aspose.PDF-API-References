---
title: "Matrix.Skew"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Matrix メソッド。指定された回転角度の行列を作成します"
type: docs
weight: 30
url: /ja/net/aspose.pdf/matrix/skew/
---
## Matrix.Skew method

指定された回転角度の Matrix を作成します。

```csharp
public static Matrix Skew(double alpha, double beta)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| alpha | Double | Skew の X 角度（ラジアン）。 |
| beta | Double | Skew の Y 角度（ラジアン）。 |

### 戻り値

変換行列です。

## 例

```csharp
Matrix m = Matrix.Skew(Math.PI / 2, Math.PI / 2);
```

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


