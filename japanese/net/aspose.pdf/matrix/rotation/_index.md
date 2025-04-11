---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: マトリックスメソッド。指定された回転角度のマトリックスを作成します。
type: docs
weight: 20
url: /ja/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

指定された回転角度のマトリックスを作成します。

```csharp
public static Matrix Rotation(double alpha)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alpha | Double | ラジアンでの回転角度。 |

### 戻り値

変換マトリックス。

## 例

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### 参照

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

指定された回転のマトリックスを作成します。

```csharp
public static Matrix Rotation(Rotation rotation)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rotation | Rotation | 回転。 有効な値は: None, on90, on180, on270 |

### 戻り値

回転を含むマトリックス。

### 参照

* 列挙型 [Rotation](../../rotation/)
* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)