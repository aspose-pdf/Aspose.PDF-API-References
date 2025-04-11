---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: طريقة المصفوفة. تنشئ مصفوفة لزاوية الدوران المعطاة
type: docs
weight: 20
url: /ar/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

تنشئ مصفوفة لزاوية الدوران المعطاة.

```csharp
public static Matrix Rotation(double alpha)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| alpha | Double | زاوية الدوران بالراديان. |

### قيمة الإرجاع

مصفوفة التحويل.

## أمثلة

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

تنشئ مصفوفة للدوران المعطى.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rotation | Rotation | الدوران. القيم الصالحة هي: None, on90, on180, on270 |

### قيمة الإرجاع

مصفوفة مع الدوران.

### انظر أيضًا

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)