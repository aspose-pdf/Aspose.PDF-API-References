---
title: "Matrix.UnTransform"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Matrix. Mengembalikan x1 dan y1 serta mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut x  D  x1  C  y1  C  F / A  D  C  B y  A  y1  B  x1  B  E / A  D  C  B"
type: docs
weight: 230
url: /id/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform method

Mengembalikan transformasi x1 dan y1 serta mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | Double | Koordinat X masukan |
| y1 | Double | Koordinat Y masukan |
| x | Double& | Koordinat X keluaran |
| y | Double& | Koordinat Y keluaran |

### Lihat Juga

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


