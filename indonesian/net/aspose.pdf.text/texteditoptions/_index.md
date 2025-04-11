---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.TextEditOptions. Menjelaskan opsi operasi pengeditan teks
type: docs
weight: 10820
url: /id/net/aspose.pdf.text/texteditoptions/
---
## Kelas TextEditOptions

Menjelaskan opsi operasi pengeditan teks.

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
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Mendapatkan atau menetapkan nilai yang mengizinkan penggunaan transformasi bahasa selama penambahan atau pengeditan teks. true - transformasi bahasa akan diterapkan jika perlu (nilai default). false - transformasi bahasa TIDAK akan diterapkan. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Mendapatkan mode untuk memproses jalur pemotongan dari teks yang diedit. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Mendapatkan mode yang mendefinisikan perilaku untuk skenario penggantian font. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Mendapatkan mode yang mendefinisikan perilaku untuk skenario transformasi bahasa. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Mendapatkan atau menetapkan mode yang mendefinisikan perilaku jika font tidak mengandung karakter yang diminta. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Mendapatkan atau menetapkan font yang digunakan untuk menggantikan jika font pengguna tidak mengandung karakter yang diperlukan |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Mendapatkan atau menetapkan nilai yang mengizinkan pencarian untuk garis bawah teks di halaman dokumen sumber. (Usang) Silakan gunakan TextSearchOptions.SearchForTextRelatedGraphics sebagai gantinya. |

### Lihat Juga

* kelas [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)