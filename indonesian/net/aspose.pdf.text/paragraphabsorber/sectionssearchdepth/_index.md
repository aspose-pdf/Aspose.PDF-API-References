---
title: "ParagraphAbsorber.SectionsSearchDepth"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti ParagraphAbsorber. Mendapatkan atau mengatur nilai yang menentukan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan. Kedalaman pencarian default adalah 3. Artinya tiga pencarian untuk bagian, header, paragraf, dll yang dibagi secara horizontal dan tiga pencarian untuk yang dibagi secara vertikal seperti kolom."
type: docs
weight: 50
url: /id/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth property

Mendapatkan atau mengatur nilai yang menentukan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan. Kedalaman pencarian default adalah 3. Artinya tiga pencarian untuk bagian yang dibagi secara horizontal (header, paragraf, dll) dan tiga pencarian untuk bagian yang dibagi secara vertikal (kolom).

```csharp
public int SectionsSearchDepth { get; set; }
```

## Catatan

Meningkatkan nilai ini dapat menyebabkan penurunan kinerja minor tanpa perubahan terlihat pada hasil pencarian. Menurunkan nilai ini dapat menyebabkan penentuan paragraf dalam bagian yang tidak tepat. Kami tidak menyarankan untuk mengatur nilai di bawah default jika Anda tidak menginginkan hanya elemen 'kasar' dari struktur halaman.

### Lihat Juga

* class [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


