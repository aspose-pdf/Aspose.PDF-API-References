---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: طريقة Matrix. تحويل الدوران إلى درجات الزاوية
type: docs
weight: 240
url: /ar/net/aspose.pdf/matrix/getangle/
---
## طريقة Matrix.GetAngle

تحويل الدوران إلى زاوية (درجات)

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
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)