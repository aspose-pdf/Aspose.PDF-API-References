---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Annotations.XYZExplicitDestination. Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat kiri atas yang diposisikan di sudut kiri atas jendela dan konten halaman diperbesar dengan faktor zoom. Nilai null untuk parameter kiri, atas, atau zoom menunjukkan bahwa nilai saat ini dari parameter tersebut akan dipertahankan tanpa perubahan. Nilai zoom 0 memiliki arti yang sama dengan nilai null.
type: docs
weight: 2730
url: /id/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## Kelas XYZExplicitDestination

Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat (kiri, atas) yang diposisikan di sudut kiri atas jendela dan konten halaman diperbesar dengan faktor zoom. Nilai null untuk parameter kiri, atas, atau zoom menunjukkan bahwa nilai saat ini dari parameter tersebut akan dipertahankan tanpa perubahan. Nilai zoom 0 memiliki arti yang sama dengan nilai null.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Membuat tujuan eksplisit jarak jauh. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Membuat tujuan eksplisit lokal. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Mendapatkan koordinat horizontal kiri dari sudut kiri atas jendela. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Mendapatkan objek halaman tujuan |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Mendapatkan nomor halaman tujuan |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Mendapatkan koordinat vertikal atas dari sudut kiri atas jendela. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Mendapatkan faktor zoom. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Membuat tujuan ke lokasi yang ditentukan dari halaman dengan mempertimbangkan rotasi halaman jika diperlukan. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Membuat tujuan ke halaman yang ditentukan. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Membuat tujuan ke sudut kiri atas halaman yang ditentukan. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Mengonversi status objek menjadi nilai string. Contoh: "1 XYZ 100 200 3". |

## Contoh

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### Lihat Juga

* kelas [ExplicitDestination](../explicitdestination/)
* ruang nama [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)