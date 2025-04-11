---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: 矩阵方法。将旋转转换为角度（度）
type: docs
weight: 240
url: /zh/net/aspose.pdf/matrix/getangle/
---
## Matrix.GetAngle 方法

将旋转转换为角度（度）

```csharp
public static double GetAngle(Rotation rotation)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotation | Rotation | 旋转值。 |

### 返回值

角度值。

## 示例

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### 另请参阅

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)