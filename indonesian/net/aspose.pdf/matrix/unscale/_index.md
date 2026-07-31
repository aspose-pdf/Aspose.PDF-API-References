---
title: "Matrix.UnScale"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Matrix. Mengembalikan skala kembali x1 dan y1 serta mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut x  D  x1  C  y1 / A  D  C  B y  A y1  B x1 / A D  C B"
type: docs
weight: 220
url: /id/net/aspose.pdf/matrix/unscale/
---
## Matrix.UnScale method

Menskalakan kembali x1 dan y1 serta mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
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


