---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: Metode Matrix. Mengubah skala x dan y dengan matriks menggunakan rumus berikut x1  Ax  Cy y1  Bx  Dy
type: docs
weight: 190
url: /id/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

Mengubah skala x dan y dengan matriks menggunakan rumus berikut: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | Double | Koordinat X input |
| y | Double | Koordinat Y input |
| x1 | Double& | Koordinat X output |
| y1 | Double& | Koordinat Y output |

### Lihat Juga

* kelas [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

Menerapkan skala pada matriks yang diberikan.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | Double | Faktor skala untuk sumbu X. |
| sy | Double | Faktor skala untuk sumbu Y. |
| source | Matrix | Matriks yang akan diubah skala. |

### Nilai Kembali

Matriks baru yang merupakan hasil dari pengubahan skala matriks sumber.

### Lihat Juga

* kelas [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)