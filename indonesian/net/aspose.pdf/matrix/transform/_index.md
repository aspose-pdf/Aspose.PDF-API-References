---
title: "Matrix.Transform"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Matrix. Mengubah titik menggunakan matrix ini."
type: docs
weight: 210
url: /id/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Mengubah titik menggunakan matriks ini.

```csharp
public Point Transform(Point p)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | Titik | Titik yang akan diubah. |

### Nilai Kembalian

Hasil transformasi.

## Contoh

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### Lihat Juga

* class [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Mengubah koordinat menggunakan matriks ini.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | Double | Koordinat X. |
| y | Double | Koordinat Y. |
| x1 | Double& | Koordinat X yang diubah. |
| y1 | Double& | Koordinat Y yang diubah. |

## Contoh

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### Lihat Juga

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Mengubah persegi panjang. Jika sudut bukan kelipatan 90 derajat maka persegi panjang pembatas yang dikembalikan.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Rectangle yang akan diubah. |

### Nilai Kembalian

Rectangle yang diubah.

## Contoh

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### Lihat Juga

* class [Rectangle](../../rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


