---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType. Enum ini menggambarkan langkah-langkah antialiasing yang mungkin selama konversi
type: docs
weight: 5570
url: /id/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## Enumerasi HtmlSaveOptions.AntialiasingProcessingType

Enum ini menggambarkan langkah-langkah antialiasing yang mungkin selama konversi

```csharp
public enum AntialiasingProcessingType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | tidak ada pemrosesan antialiasing khusus yang digunakan. Ini adalah opsi optimal untuk mayoritas besar dokumen dan tidak memerlukan waktu tambahan selama konversi |
| TryCorrectResultHtml | `1` | Dalam hal ini, konverter mencoba mendeteksi tempat dengan elemen grafis latar belakang yang berdekatan dan memperbaiki HTML hasil dengan cara yang relevan. Opsi ini memungkinkan meningkatkan hasil ekspor untuk dokumen yang mengandung latar belakang yang dibangun dari beberapa elemen grafis yang berdekatan (untuk jenis dokumen ini, perender PDF, misalnya Acrobat Reader, biasanya mencoba memperhalus batas elemen selama perenderan. Dengan opsi ini, konverter meniru perilaku perender PDF. Opsi ini memungkinkan meningkatkan tata letak hasil ekspor untuk beberapa dokumen spesifik (yang menggunakan latar belakang komposit semacam itu), tetapi memerlukan waktu tambahan untuk pemrosesan (biasanya sekitar 10-15% waktu tambahan). Jadi penggunaan mode ini dalam kasus umum tidak disarankan. |

### Lihat Juga

* kelas [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)