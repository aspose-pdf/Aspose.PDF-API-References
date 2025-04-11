---
title: Class TextElement
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Structure.TextElement. Elemen teks umum dari struktur logis dokumen
type: docs
weight: 10190
url: /id/net/aspose.pdf.structure/textelement/
---
## Kelas TextElement

Elemen teks umum dari struktur logis dokumen.

```csharp
public class TextElement : Element
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Opsional; PDF 1.4) Teks yang merupakan pengganti tepat untuk elemen struktur dan anak-anaknya. Teks pengganti ini (yang seharusnya berlaku untuk bagian konten sekecil mungkin) berguna saat mengekstrak konten dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lainnya. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Opsional) Deskripsi alternatif dari elemen struktur dan anak-anaknya dalam bentuk yang dapat dibaca manusia, yang berguna saat mengekstrak konten dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lainnya. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Mendapatkan koleksi elemen anak. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Opsional; PDF 1.5) Bentuk diperluas dari singkatan. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Opsional; PDF 1.4) Sebuah bahasa yang menentukan bahasa alami untuk semua teks dalam elemen struktur kecuali di mana ditimpa oleh spesifikasi bahasa untuk elemen struktur bersarang atau konten yang ditandai. |
| [Text](../../aspose.pdf.structure/textelement/text/) { get; } | Mendapatkan nilai dari elemen struktur teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Menghapus elemen. |

### Lihat Juga

* kelas [Element](../element/)
* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)