---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.SaveOptions. Tipe SaveOptions menyimpan tingkat abstraksi pada opsi penyimpanan individu
type: docs
weight: 9870
url: /id/net/aspose.pdf/saveoptions/
---
## Kelas SaveOptions

Tipe SaveOptions menyimpan tingkat abstraksi pada opsi penyimpanan individu

```csharp
public abstract class SaveOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glyph font akan disimpan dalam cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi pdf ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format data yang disimpan. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah akan Melanjutkan atau Menghentikan. Melanjutkan adalah tindakan default dan operasi Simpan berlanjut, namun pengguna juga dapat mengembalikan Menghentikan di mana kasus operasi Simpan harus dihentikan. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)