---
title: "Enum TextReplaceOptions.ReplaceAdjustment"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment. Menentukan aksi yang akan dilakukan setelah mengganti fragmen teks menjadi lebih pendek. None tidak ada aksi; teks yang diganti dapat tumpang tindih dengan sisa baris. AdjustSpaceWidth mencoba menyesuaikan spasi antar kata untuk menjaga panjang baris. WholeWordsHyphenation mencoba mendistribusikan kata antar baris paragraf untuk menjaga bidang kanan paragraf. ShiftRestOfLine menggeser sisa baris sesuai perubahan panjang teks; panjang baris dapat berubah. Nilai default adalah ShiftRestOfLine."
type: docs
weight: 11210
url: /id/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

Menentukan aksi yang akan dilakukan setelah mengganti fragmen teks menjadi lebih pendek. None - tidak ada aksi, teks yang diganti dapat tumpang tindih dengan sisa baris; AdjustSpaceWidth - mencoba menyesuaikan spasi antar kata untuk menjaga panjang baris; WholeWordsHyphenation - mencoba mendistribusikan kata antar baris paragraf untuk menjaga bidang kanan paragraf; ShiftRestOfLine - menggeser sisa baris sesuai perubahan panjang teks, panjang baris dapat berubah; Nilai default adalah ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Tidak ada aksi, teks yang diganti dapat tumpang tindih dengan sisa baris |
| AdjustSpaceWidth | `1` | Mencoba menyesuaikan spasi antar kata untuk menjaga panjang baris |
| WholeWordsHyphenation | `2` | Mencoba mendistribusikan kata antar baris paragraf untuk menjaga bidang kanan paragraf |
| IsFormFillingMode | `4` | Mencoba menyebarkan kata dalam ruang putih yang tersedia menggunakan lebar paragraf. Jika teks meluap, akan disembunyikan. |
| ShiftRestOfLine | `8` | (Default) Menggeser sisa baris sesuai dengan perubahan panjang teks, panjang baris dapat diubah |

### Lihat Juga

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


