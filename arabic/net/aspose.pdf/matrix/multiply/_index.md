---
title: "Matrix.Multiply"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Matrix. يضرب المصفوفة بمصفوفة أخرى"
type: docs
weight: 170
url: /ar/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply method

يضرب المصفوفة في مصفوفة أخرى.

```csharp
public Matrix Multiply(Matrix other)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| آخر | Matrix | مصفوفة الضارب. |

### قيمة الإرجاع

نتيجة الضرب.

## أمثلة

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


