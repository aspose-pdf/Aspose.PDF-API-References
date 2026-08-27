---
title: "Matrix.Scale"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Matrix. Menskalakan x dan y dengan matriks menggunakan rumus berikut x1  Ax  Cy y1  Bx  Dy"
type: docs
weight: 190
url: /id/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

Menskalakan x dan y dengan matriks menggunakan rumus berikut: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | Double | Koordinat X masukan |
| y | Double | Koordinat Y masukan |
| x1 | Double& | Koordinat X keluaran |
| y1 | Double& | Koordinat Y keluaran |

### Lihat Juga

* class [Matrix](../)
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
| sumber | Matrix | Matriks yang akan diskalakan. |

### Nilai Kembalian

Matriks baru yang merupakan hasil skala matriks sumber.

### Lihat Juga

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


