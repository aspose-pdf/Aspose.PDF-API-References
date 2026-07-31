---
title: "Enum HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType. Enum ini menjelaskan langkah antialiasing yang mungkin selama konversi"
type: docs
weight: 5700
url: /id/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

Enum ini menjelaskan langkah antialiasing yang mungkin selama konversi

```csharp
public enum AntialiasingProcessingType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | Tidak ada pemrosesan antialiasing khusus yang digunakan. Ini adalah opsi optimal untuk mayoritas dokumen dan tidak memerlukan waktu tambahan selama konversi. |
| TryCorrectResultHtml | `1` | Dalam kasus seperti itu, konverter berusaha mendeteksi area dengan elemen grafis latar belakang yang bersebelahan dan memperbaiki HTML hasil secara relevan. Opsi ini memungkinkan meningkatkan hasil ekspor untuk dokumen yang berisi latar belakang yang dibangun dari beberapa elemen grafis bersebelahan (untuk jenis dokumen seperti itu, renderer PDF, misalnya Acrobat Reader, biasanya mencoba memperhalus batas elemen selama rendering. Dengan opsi ini, konverter meniru perilaku renderer PDF). Opsi ini memungkinkan meningkatkan tata letak hasil ekspor untuk beberapa dokumen spesifik (yang menggunakan latar belakang komposit semacam itu), tetapi memerlukan waktu tambahan untuk pemrosesan (biasanya sekitar 10‑15% waktu tambahan). Oleh karena itu, penggunaan mode ini dalam kasus umum tidak disarankan. |

### Lihat Juga

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


