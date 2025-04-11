---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.DocSaveOptionsRecognitionMode. Memungkinkan untuk mengontrol bagaimana dokumen PDF dikonversi menjadi dokumen pengolah kata
type: docs
weight: 3770
url: /id/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## Enumerasi DocSaveOptions.RecognitionMode

Memungkinkan untuk mengontrol bagaimana dokumen PDF dikonversi menjadi dokumen pengolah kata.

```csharp
public enum RecognitionMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Textbox | `0` | Mode ini cepat dan baik untuk mempertahankan tampilan asli file PDF, tetapi kemampuan edit dari dokumen yang dihasilkan bisa terbatas. |
| Flow | `1` | Mode pengenalan penuh, mesin melakukan pengelompokan dan analisis multi-level untuk mengembalikan niat asli penulis dokumen dan menghasilkan dokumen yang dapat diedit secara maksimal. Kekurangannya adalah dokumen keluaran mungkin terlihat berbeda dari file PDF asli. |
| EnhancedFlow | `2` | Mode Flow alternatif yang mendukung pengenalan tabel. |

## Catatan

Gunakan mode Textbox ketika dokumen yang dihasilkan tidak akan banyak diedit lebih lanjut. Textbox mudah dimodifikasi ketika tidak banyak yang perlu dilakukan.

Gunakan mode Flow ketika dokumen keluaran memerlukan pengeditan lebih lanjut. Paragraf dan garis teks dalam mode flow memungkinkan modifikasi teks yang mudah, tetapi objek format yang tidak didukung akan terlihat lebih buruk dibandingkan dengan mode Textbox.

### Lihat Juga

* kelas [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)