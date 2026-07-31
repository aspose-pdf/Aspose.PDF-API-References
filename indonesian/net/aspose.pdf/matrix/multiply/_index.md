---
title: "Matrix.Multiply"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Matrix. Mengalikan matrix dengan matrix lain."
type: docs
weight: 170
url: /id/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply method

Mengalikan matriks dengan matriks lain.

```csharp
public Matrix Multiply(Matrix other)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lainnya | Matrix | Matrix pengganda. |

### Nilai Kembalian

Hasil perkalian.

## Contoh

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Lihat Juga

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


