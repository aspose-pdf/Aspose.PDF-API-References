---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: طريقة المصفوفة. تضرب المصفوفة بمصفوفة أخرى
type: docs
weight: 170
url: /ar/net/aspose.pdf/matrix/multiply/
---
## طريقة Matrix.Multiply

تضرب المصفوفة بمصفوفة أخرى.

```csharp
public Matrix Multiply(Matrix other)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | Matrix | مصفوفة الضرب. |

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