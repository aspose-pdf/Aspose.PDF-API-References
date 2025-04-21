---
title: Matrix.UnScale
second_title: Aspose.PDF for .NET API Reference
description: Metode Matriks. Mengembalikan x1 dan y1 dan mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut x = D  x1 - C  y1 / A  D - C  B; y = A y1 - B x1 / A D - C B;
type: docs
weight: 220
url: /id/net/aspose.pdf/matrix/unscale/
---
## Metode Matrix.UnScale

Mengembalikan x1 dan y1 dan mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | Double | Koordinat X input |
| y1 | Double | Koordinat Y input |
| x | Double& | Koordinat X output |
| y | Double& | Koordinat Y output |

### Lihat Juga

* kelas [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)