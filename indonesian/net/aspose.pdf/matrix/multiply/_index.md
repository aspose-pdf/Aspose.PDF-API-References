---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: Metode Matriks. Mengalikan matriks dengan matriks lainnya
type: docs
weight: 170
url: /id/net/aspose.pdf/matrix/multiply/
---
## Metode Matrix.Multiply

Mengalikan matriks dengan matriks lainnya.

```csharp
public Matrix Multiply(Matrix other)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | Matriks | Matriks pengali. |

### Nilai Kembali

Hasil dari perkalian.

## Contoh

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Lihat Juga

* kelas [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)