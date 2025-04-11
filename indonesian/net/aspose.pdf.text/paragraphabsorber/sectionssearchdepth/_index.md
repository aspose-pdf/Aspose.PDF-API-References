---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: Properti ParagraphAbsorber. Mendapatkan atau menetapkan nilai yang menginstruksikan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan. Kedalaman pencarian default adalah 3. Ini berarti tiga pencarian untuk bagian yang dibagi secara horizontal (header, paragraf, dll) dan tiga pencarian untuk yang dibagi secara vertikal (kolom).
type: docs
weight: 50
url: /id/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## Properti ParagraphAbsorber.SectionsSearchDepth

Mendapatkan atau menetapkan nilai yang menginstruksikan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan. Kedalaman pencarian default adalah 3. Ini berarti tiga pencarian untuk bagian yang dibagi secara horizontal (header, paragraf, dll) dan tiga pencarian untuk yang dibagi secara vertikal (kolom).

```csharp
public int SectionsSearchDepth { get; set; }
```

## Catatan

Peningkatan nilai ini dapat menyebabkan penurunan kinerja yang minor tanpa perubahan yang terlihat dalam hasil pencarian. Penurunan nilai ini dapat menyebabkan penentuan paragraf yang tidak tepat dalam bagian. Kami tidak merekomendasikan untuk menetapkan nilai kurang dari default jika Anda tidak ingin mendapatkan hanya elemen 'kasar' dari struktur halaman.

### Lihat Juga

* kelas [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)