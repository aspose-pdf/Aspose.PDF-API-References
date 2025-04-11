---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Rectangle. Kelas ini merepresentasikan persegi panjang
type: docs
weight: 9750
url: /id/net/aspose.pdf/rectangle/
---
## Kelas Rectangle

Kelas ini merepresentasikan persegi panjang.

```csharp
public sealed class Rectangle : ICloneable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Konstruktor dari Rectangle. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Persegi panjang kosong |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Menginisialisasi persegi panjang trivial yaitu persegi panjang dengan posisi dan ukuran nol. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Tinggi dari persegi panjang. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Memeriksa apakah persegi panjang kosong. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Memeriksa apakah persegi panjang adalah titik yaitu LLX sama dengan URX dan LLY sama dengan URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Memeriksa apakah persegi panjang trivial yaitu memiliki ukuran dan posisi nol. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | Koordinat X dari sudut kiri bawah. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Koordinat Y dari sudut kiri bawah. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | Koordinat X dari sudut kanan atas. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Koordinat Y dari sudut kanan atas. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Lebar dari persegi panjang. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Menginisialisasi persegi panjang baru dari instance yang diberikan dari System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Menginisialisasi persegi panjang baru dari instance yang diberikan dari System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Mencoba untuk mengurai string dan mengekstrak dari komponen persegi panjang llx, lly, urx, ury. |
| [Center](../../aspose.pdf/rectangle/center/)() | Mengembalikan koordinat pusat dari persegi panjang. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Mengkloning objek Rectangle. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Menentukan apakah titik yang diberikan berada di dalam persegi panjang. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Menentukan apakah persegi panjang mengandung garis yang diwakili oleh dua titik. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Menentukan apakah titik yang diberikan berada di dalam persegi panjang. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Memeriksa apakah persegi panjang sama yaitu memiliki posisi dan ukuran yang sama. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Menginterseksi dua persegi panjang. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Menentukan apakah persegi panjang ini berpotongan dengan persegi panjang lainnya. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Menggabungkan persegi panjang. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Menggeser persegi panjang dengan delta yang ditentukan. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Memeriksa apakah persegi panjang hampir sama yaitu memiliki posisi dan ukuran yang hampir sama (hingga delta). |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Memutar persegi panjang dengan sudut yang ditentukan. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Memutar persegi panjang dengan sudut yang ditentukan. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Mengonversi persegi panjang menjadi array titik ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Mengonversi persegi panjang menjadi instance dari System.Drawing.Rectangle. Posisi dan ukuran floating-point dipotong. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Mendapatkan representasi string dari persegi panjang. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)