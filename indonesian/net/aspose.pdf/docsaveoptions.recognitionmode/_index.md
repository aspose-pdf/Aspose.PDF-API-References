---
title: "Enum DocSaveOptions.RecognitionMode"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.DocSaveOptionsRecognitionMode enum. Memungkinkan mengontrol bagaimana dokumen PDF dikonversi menjadi dokumen pengolah kata."
type: docs
weight: 3890
url: /id/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode enumeration

Memungkinkan mengontrol bagaimana dokumen PDF dikonversi menjadi dokumen pengolah kata.

```csharp
public enum RecognitionMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Textbox | `0` | Mode ini cepat dan baik untuk mempertahankan tampilan asli file PDF secara maksimal, tetapi kemampuan mengedit Document yang dihasilkan dapat terbatas. |
| Flow | `1` | Mode pengenalan penuh, mesin melakukan pengelompokan dan analisis multi‑tingkat untuk mengembalikan maksud penulis Document asli dan menghasilkan Document yang dapat diedit secara maksimal. Kekurangannya, Document output mungkin terlihat berbeda dari file PDF asli. |
| EnhancedFlow | `2` | Mode Flow alternatif yang mendukung pengenalan tabel. |

## Catatan

Gunakan mode Textbox ketika dokumen hasil tidak akan banyak diedit lebih lanjut. Textbox mudah dimodifikasi ketika tidak banyak yang harus dilakukan.

Gunakan mode Flow ketika dokumen output memerlukan penyuntingan lebih lanjut. Paragraf dan baris teks dalam mode flow memungkinkan modifikasi teks yang mudah, tetapi objek format yang tidak didukung akan terlihat lebih buruk dibandingkan mode Textbox.

### Lihat Juga

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


