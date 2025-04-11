---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Structure.Element. Kelas yang mewakili elemen dasar dari struktur logis
type: docs
weight: 10140
url: /id/net/aspose.pdf.structure/element/
---
## Kelas Elemen

Kelas yang mewakili elemen dasar dari struktur logis.

```csharp
public abstract class Element
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Opsional; PDF 1.4) Teks yang merupakan pengganti tepat untuk elemen struktur dan anak-anaknya. Teks pengganti ini (yang seharusnya diterapkan pada bagian konten sekecil mungkin) berguna saat mengekstrak konten dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lainnya. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Opsional) Deskripsi alternatif dari elemen struktur dan anak-anaknya dalam bentuk yang dapat dibaca manusia, yang berguna saat mengekstrak konten dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lainnya. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Mendapatkan koleksi elemen anak. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Opsional; PDF 1.5) Bentuk yang diperluas dari singkatan. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Opsional; PDF 1.4) Sebuah bahasa yang menentukan bahasa alami untuk semua teks dalam elemen struktur kecuali di mana ditimpa oleh spesifikasi bahasa untuk elemen struktur bersarang atau konten yang ditandai. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Menghapus elemen. |

### Lihat Juga

* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)