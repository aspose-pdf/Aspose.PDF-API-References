---
title: "Matrix3D.GetAngle"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Matrix3D. تحوّل الدوران إلى درجات الزاوية."
type: docs
weight: 180
url: /ar/net/aspose.pdf/matrix3d/getangle/
---
## Matrix3D.GetAngle method

يحوّل الدوران إلى زاوية (بالدرجات)

```csharp
public static double GetAngle(Rotation rotation)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| دوران | دوران | قيمة الدوران. |

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


