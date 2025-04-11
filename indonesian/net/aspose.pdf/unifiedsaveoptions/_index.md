---
title: Class UnifiedSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.UnifiedSaveOptions. Kelas ini mewakili opsi penyimpanan untuk penyimpanan yang menggunakan cara konversi terpadu dengan model dokumen internal terpadu
type: docs
weight: 11140
url: /id/net/aspose.pdf/unifiedsaveoptions/
---
## Kelas UnifiedSaveOptions

Kelas ini mewakili opsi penyimpanan untuk penyimpanan yang menggunakan cara konversi terpadu (dengan model dokumen internal terpadu)

```csharp
public class UnifiedSaveOptions : SaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [UnifiedSaveOptions](unifiedsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau menetapkan nilai boolean yang menunjukkan apakah glyph font akan disimpan sementara saat menyiapkan halaman aps. Meningkatkan kinerja konversi pdf ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau menetapkan nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks untuk dokumen PDF dengan sublayer OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Melanjutkan atau Membatalkan. Melanjutkan adalah tindakan default dan operasi Simpan berlanjut, namun pengguna juga dapat mengembalikan Membatalkan di mana operasi Simpan harus dihentikan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Memproses halaman dalam beberapa utas. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF mengandung gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang yang sama yang diletakkan berdekatan satu sama lain. Dalam kasus seperti itu, perender format target (misalnya MsWord untuk format DOCS) terkadang menghasilkan batas yang terlihat antara bagian gambar latar belakang, karena teknik mereka dalam penghalusan tepi gambar (anti-aliasing) berbeda dari Acrobat Reader. Jika terlihat bahwa dokumen yang diekspor mengandung batas yang terlihat antara bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan itu. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, silakan gunakan opsi ini hanya ketika benar-benar diperlukan. |

### Lihat Juga

* kelas [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)