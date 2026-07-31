---
title: "Kelas TextReplaceOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.TextReplaceOptions. Mewakili opsi penggantian teks"
type: docs
weight: 11190
url: /id/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class

Mewakili opsi penggantian teks

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Menginisialisasi instance baru dari objek `TextReplaceOptions` untuk aksi setelah penggantian yang ditentukan. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Menginisialisasi instance baru dari objek `TextReplaceOptions` untuk ruang lingkup yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Mendapatkan atau mengatur nilai spasi baris yang digunakan jika penyesuaian penggantian dipaksa membuat baris teks baru. Nilai yang diharapkan adalah pengganda ukuran font teks yang diganti. Default adalah 1,2. |
| [FontSizeAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/fontsizeadjustmentaction/) { get; set; } | Mendapatkan atau mengatur kebijakan penyesuaian ukuran font agar sesuai dengan batas yang didefinisikan oleh [`Rectangle`](./rectangle/). |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah harus mengabaikan paragraf terpisah saat menyesuaikan teks pada halaman setelah penggantian teks. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Mengatur atau mendapatkan penyesuaian posisi kiri untuk teks yang diganti saat menggunakan TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [Rectangle](../../aspose.pdf.text/textreplaceoptions/rectangle/) { get; set; } | Mendapatkan atau mengatur rectangle untuk menyesuaikan teks setelah penggantian. |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Mendapatkan atau mengatur aksi yang akan dilakukan setelah mengganti fragmen teks menjadi lebih singkat. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Mendapatkan atau mengatur ruang lingkup di mana operasi penggantian teks diterapkan |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Mengatur atau mendapatkan penyesuaian posisi kanan untuk teks yang diganti saat menggunakan TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### Lihat Juga

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


