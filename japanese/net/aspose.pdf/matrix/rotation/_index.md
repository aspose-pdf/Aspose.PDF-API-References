---
title: "Matrix.Rotation"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Matrix メソッド。指定された回転角度の行列を作成します"
type: docs
weight: 20
url: /ja/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

指定された回転角度の Matrix を作成します。

```csharp
public static Matrix Rotation(double alpha)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| alpha | Double | ラジアン単位の回転角度。 |

### 戻り値

変換行列です。

## 例

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

指定された回転の Matrix を作成します。

```csharp
public static Matrix Rotation(Rotation rotation)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 回転 | 回転 | 回転。有効な値は: None, on90, on180, on270 |

### 戻り値

回転付き Matrix。

### 関連項目

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


