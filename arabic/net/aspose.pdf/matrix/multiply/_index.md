---
title: Multiply
second_title: Aspose.PDF لمرجع .NET API
description: ضرب المصفوفة في مصفوفة أخرى .
type: docs
weight: 150
url: /ar/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply method

ضرب المصفوفة في مصفوفة أخرى .

```csharp
public Matrix Multiply(Matrix other)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| other | Matrix | مصفوفة المضاعف. |

### قيمة الإرجاع

نتيجة الضرب.

### أمثلة

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### أنظر أيضا

* class [Matrix](../../matrix)
* مساحة الاسم [Aspose.Pdf](../../matrix)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->