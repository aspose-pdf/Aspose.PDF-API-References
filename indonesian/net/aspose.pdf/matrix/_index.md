---
title: "Kelas Matrix"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Matrix. Kelas yang mewakili Matrix transformasi"
type: docs
weight: 7060
url: /id/net/aspose.pdf/matrix/
---
## Matrix class

Kelas mewakili matriks transformasi.

```csharp
public sealed class Matrix
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Matrix](matrix/#constructor)() | Konstruktor membuat Matrix standar 1 ke 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | Konstruktor menerima sebuah Matrix dengan representasi array berikut: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | Konstruktor menerima sebuah Matrix dengan representasi array berikut: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | Konstruktor menerima sebuah Matrix untuk membuat salinan |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Menginisialisasi Matrix transformasi dengan koefisien yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | Anggota A dari Matrix transformasi. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | Anggota B dari Matrix transformasi. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | Anggota C dari Matrix transformasi. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | Anggota D dari Matrix transformasi. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Mendapatkan data Matrix sebagai array. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | Anggota E dari Matrix transformasi. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Elemen-elemen dari Matrix. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | Anggota F dari Matrix transformasi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Membuat Matrix untuk sudut rotasi yang diberikan. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Membuat matriks untuk rotasi yang diberikan. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Menerapkan skala pada matriks yang diberikan. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Membuat Matrix untuk sudut rotasi yang diberikan. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Menerjemahkan matriks sebesar jumlah yang ditentukan pada arah x dan y. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Menambahkan matriks ke matriks lain. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Membandingkan matriks dengan objek lain. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Mendapatkan matriks pembalik. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Kode hash untuk objek. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Mengalikan matriks dengan matriks lain. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Menghitung matriks terbalik. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Menskalakan x dan y dengan matriks menggunakan rumus berikut: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Mengembalikan representasi teks dari matriks. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Mengubah titik menggunakan matriks ini. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Mengubah persegi panjang. Jika sudut bukan kelipatan 90 derajat maka persegi panjang pembatas yang dikembalikan. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Mengubah koordinat menggunakan matriks ini. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Menskalakan kembali x1 dan y1 serta mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Mengembalikan transformasi x1 dan y1 serta mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Menerjemahkan rotasi menjadi sudut (derajat) |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


