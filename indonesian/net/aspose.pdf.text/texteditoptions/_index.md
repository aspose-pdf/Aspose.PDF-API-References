---
title: "Kelas TextEditOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.TextEditOptions. Menjelaskan opsi operasi penyuntingan teks"
type: docs
weight: 11000
url: /id/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

Menjelaskan opsi operasi penyuntingan teks.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Menginisialisasi instance baru dari objek `TextEditOptions` untuk izin transformasi bahasa yang ditentukan. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Menginisialisasi instance baru dari objek `TextEditOptions` untuk mode perilaku penggantian font yang ditentukan. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Menginisialisasi instance baru dari objek `TextEditOptions` untuk mode perilaku transformasi bahasa yang ditentukan. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Menginisialisasi instance baru dari objek `TextEditOptions` untuk mode perilaku tanpa karakter yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Mendapatkan atau mengatur nilai yang mengizinkan penggunaan transformasi bahasa selama penambahan atau penyuntingan teks. true - transformasi bahasa akan diterapkan jika diperlukan (nilai default). false - transformasi bahasa TIDAK akan diterapkan. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Mendapatkan mode untuk memproses jalur pemotongan (clipping path) teks yang disunting. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Mendapatkan mode yang menentukan perilaku untuk skenario penggantian font. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Mendapatkan mode yang menentukan perilaku untuk skenario transformasi bahasa. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Mendapatkan atau mengatur mode yang menentukan perilaku bila font tidak mengandung karakter yang diminta. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Mendapatkan atau mengatur font yang digunakan untuk penggantian jika font pengguna tidak mengandung karakter yang diperlukan |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Mendapatkan atau mengatur nilai yang mengizinkan pencarian garis bawah teks pada halaman dokumen sumber. (Usang) Silakan gunakan TextSearchOptions.SearchForTextRelatedGraphics sebagai gantinya. |

### Lihat Juga

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


