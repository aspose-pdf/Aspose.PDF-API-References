---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: طريقة Matrix3D. تترجم الدوران إلى درجات الزاوية
type: docs
weight: 180
url: /ar/net/aspose.pdf/matrix3d/getangle/
---
## طريقة Matrix3D.GetAngle

تترجم الدوران إلى زاوية (درجات)

```csharp
public static double GetAngle(Rotation rotation)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rotation | Rotation | قيمة الدوران. |

### قيمة الإرجاع

قيمة الزاوية.

## أمثلة

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### انظر أيضًا

* enum [Rotation](../../rotation/)
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)