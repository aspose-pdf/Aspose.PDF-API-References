---
title: "Kelas Rectangle"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Rectangle. Kelas ini mewakili persegi panjang."
type: docs
weight: 9900
url: /id/net/aspose.pdf/rectangle/
---
## Rectangle class

Kelas mewakili persegi panjang.

```csharp
public sealed class Rectangle : ICloneable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Konstruktor Rectangle. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Rectangle kosong |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Menginisialisasi rectangle trivial, yaitu rectangle dengan posisi dan ukuran nol. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Tinggi persegi panjang. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Memeriksa apakah persegi panjang kosong. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Memeriksa apakah persegi panjang adalah titik, yaitu LLX sama dengan URX dan LLY sama dengan URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Memeriksa apakah persegi panjang bersifat trivial, yaitu memiliki ukuran dan posisi nol. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | Koordinat X sudut kiri bawah. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Koordinat Y sudut kiri bawah. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | Koordinat X sudut kanan atas. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Koordinat Y sudut kanan atas. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Lebar persegi panjang. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Menginisialisasi persegi panjang baru dari instance System.Drawing.Rectangle yang diberikan. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Menginisialisasi persegi panjang baru dari instance System.Drawing.Rectangle yang diberikan. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Mencoba mengurai string dan mengekstrak komponen persegi panjang llx, lly, urx, ury darinya. |
| [Center](../../aspose.pdf/rectangle/center/)() | Mengembalikan koordinat pusat persegi panjang. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Mengkloning objek Rectangle. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Menentukan apakah titik yang diberikan berada di dalam persegi panjang. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Menentukan apakah persegi panjang berisi garis yang direpresentasikan oleh dua titik. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Menentukan apakah titik yang diberikan berada di dalam persegi panjang. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Memeriksa apakah persegi panjang sama, yaitu memiliki posisi dan ukuran yang sama. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Berpotongan dengan persegi panjang lain. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Menentukan apakah persegi panjang ini berpotongan dengan persegi panjang lain. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Menggabungkan persegi panjang. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Menggeser persegi panjang dengan delta yang ditentukan. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Memeriksa apakah persegi panjang hampir sama, yaitu memiliki posisi dan ukuran yang hampir sama (hingga delta). |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Memutar persegi panjang dengan sudut yang ditentukan. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Memutar persegi panjang dengan sudut yang ditentukan. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Mengonversi persegi panjang menjadi array titik ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Mengonversi persegi panjang menjadi instance System.Drawing.Rectangle. Posisi dan ukuran floating-point dipotong. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Mendapatkan representasi string persegi panjang. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


