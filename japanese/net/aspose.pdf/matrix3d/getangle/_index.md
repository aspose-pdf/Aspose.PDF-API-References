---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Matrix3D メソッド。回転を角度度に変換します
type: docs
weight: 180
url: /ja/net/aspose.pdf/matrix3d/getangle/
---
## Matrix3D.GetAngle メソッド

回転を角度（度）に変換します

```csharp
public static double GetAngle(Rotation rotation)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rotation | Rotation | 回転値。 |

### 戻り値

角度値。

## 例

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### 参照

* enum [Rotation](../../rotation/)
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)