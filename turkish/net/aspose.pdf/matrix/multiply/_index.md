---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: Matris yöntemi. Matrisi diğer matrisle çarpar
type: docs
weight: 170
url: /tr/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply yöntemi

Matrisi diğer matrisle çarpar.

```csharp
public Matrix Multiply(Matrix other)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | Matrix | Çarpan matris. |

### Dönüş Değeri

Çarpma işleminin sonucu.

## Örnekler

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Ayrıca Bakınız

* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)