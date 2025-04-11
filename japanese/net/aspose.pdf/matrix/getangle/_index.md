---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Matrix メソッド。回転を角度（度）に変換します
type: docs
weight: 240
url: /ja/net/aspose.pdf/matrix/getangle/
---
## Matrix.GetAngle メソッド

回転を角度（度）に変換します

```csharp
public static double GetAngle(Rotation rotation)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rotation | Rotation | 回転値。 |

### 戻り値

角度の値。

## 例

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### 関連項目

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)