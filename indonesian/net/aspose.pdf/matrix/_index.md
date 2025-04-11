---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Matrix. Kelas ini mewakili matriks transformasi
type: docs
weight: 6920
url: /id/net/aspose.pdf/matrix/
---
## Kelas Matriks

Kelas ini mewakili matriks transformasi.

```csharp
public sealed class Matrix
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Matrix](matrix/#constructor)() | Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | Konstruktor menerima matriks dengan representasi array berikut: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | Konstruktor menerima matriks dengan representasi array berikut: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | Konstruktor menerima matriks untuk membuat salinan |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Menginisialisasi matriks transformasi dengan koefisien yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | Anggota dari matriks transformasi. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | Anggota B dari matriks transformasi. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | Anggota C dari matriks transformasi. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | Anggota D dari matriks transformasi. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Mendapatkan data dari Matriks sebagai array. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | Anggota E dari matriks transformasi. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Elemen dari matriks. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | Anggota F dari matriks transformasi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Membuat matriks untuk sudut rotasi yang diberikan. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Membuat matriks untuk rotasi yang diberikan. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Menerapkan skala pada matriks yang diberikan. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Membuat matriks untuk sudut rotasi yang diberikan. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Menerjemahkan matriks dengan jumlah yang ditentukan dalam arah x dan y. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Menambahkan matriks ke matriks lain. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Membandingkan matriks dengan objek lain. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Mendapatkan matriks flipping. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Kode hash untuk objek. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Mengalikan matriks dengan matriks lain. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Menghitung matriks terbalik. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Mengskala x dan y dengan matriks menggunakan rumus berikut: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Mengembalikan representasi teks dari matriks. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Mentransformasikan titik menggunakan matriks ini. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Mentransformasikan persegi panjang. Jika sudut bukan 90 * N derajat maka persegi panjang pembatas dikembalikan. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Mentransformasikan koordinat menggunakan matriks ini. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Mengembalikan skala x1 dan y1 dan mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Mentransformasikan kembali x1 dan y1 dan mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Menerjemahkan rotasi menjadi sudut (derajat) |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)