---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Enum ini menjelaskan langkah antialiasing yang mungkin selama konversi"
type: docs
weight: 2000
url: /id/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

Enum ini menjelaskan langkah antialiasing yang mungkin selama konversi

## Fields

| Field | Deskripsi |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | Tidak ada pemrosesan antialiasing khusus yang digunakan. Ini adalah opsi optimal untuk mayoritas dokumen dan tidak memerlukan waktu tambahan selama konversi. |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | Dalam kasus seperti itu konverter mencoba mendeteksi area dengan elemen grafis latar belakang yang berdekatan dan memperbaiki HTML hasil secara relevan. Opsi ini memungkinkan peningkatan hasil ekspor untuk dokumen yang berisi latar belakang yang dibangun dari beberapa elemen grafis berdekatan (untuk jenis dokumen tersebut, renderer PDF, misalnya Acrobat Reader, biasanya mencoba memperhalus batas elemen selama rendering. Dengan opsi ini konverter meniru perilaku renderer PDF). Opsi ini memungkinkan peningkatan tata letak hasil ekspor untuk beberapa dokumen spesifik (yang menggunakan latar belakang komposit), tetapi memerlukan waktu tambahan untuk pemrosesan (biasanya sekitar 10‑15 % waktu tambahan). Jadi penggunaan mode ini dalam kasus umum tidak disarankan. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

Tidak ada pemrosesan antialiasing khusus yang digunakan. Ini adalah opsi optimal untuk mayoritas dokumen dan tidak memerlukan waktu tambahan selama konversi.

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

Dalam kasus seperti itu konverter mencoba mendeteksi area dengan elemen grafis latar belakang yang berdekatan dan memperbaiki HTML hasil secara relevan. Opsi ini memungkinkan peningkatan hasil ekspor untuk dokumen yang berisi latar belakang yang dibangun dari beberapa elemen grafis berdekatan (untuk jenis dokumen tersebut, renderer PDF, misalnya Acrobat Reader, biasanya mencoba memperhalus batas elemen selama rendering. Dengan opsi ini konverter meniru perilaku renderer PDF). Opsi ini memungkinkan peningkatan tata letak hasil ekspor untuk beberapa dokumen spesifik (yang menggunakan latar belakang komposit), tetapi memerlukan waktu tambahan untuk pemrosesan (biasanya sekitar 10‑15 % waktu tambahan). Jadi penggunaan mode ini dalam kasus umum tidak disarankan.
