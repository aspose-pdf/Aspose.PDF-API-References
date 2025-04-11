---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment enum. Menentukan tindakan yang akan dilakukan setelah penggantian fragmen teks menjadi lebih pendek. None - tidak ada tindakan, teks yang diganti mungkin tumpang tindih dengan sisa baris; AdjustSpaceWidth - mencoba menyesuaikan spasi antara kata untuk menjaga panjang baris; WholeWordsHyphenation - mencoba mendistribusikan kata-kata antara baris paragraf untuk menjaga bidang kanan paragraf; ShiftRestOfLine - menggeser sisa baris sesuai dengan perubahan panjang teks, panjang baris mungkin berubah; Nilai default adalah ShiftRestOfLine.
type: docs
weight: 11020
url: /id/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## Enumerasi TextReplaceOptions.ReplaceAdjustment

Menentukan tindakan yang akan dilakukan setelah penggantian fragmen teks menjadi lebih pendek. None - tidak ada tindakan, teks yang diganti mungkin tumpang tindih dengan sisa baris; AdjustSpaceWidth - mencoba menyesuaikan spasi antara kata untuk menjaga panjang baris; WholeWordsHyphenation - mencoba mendistribusikan kata-kata antara baris paragraf untuk menjaga bidang kanan paragraf; ShiftRestOfLine - menggeser sisa baris sesuai dengan perubahan panjang teks, panjang baris mungkin berubah; Nilai default adalah ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Tidak ada tindakan, teks yang diganti mungkin tumpang tindih dengan sisa baris |
| AdjustSpaceWidth | `1` | Mencoba menyesuaikan spasi antara kata untuk menjaga panjang baris |
| WholeWordsHyphenation | `2` | Mencoba mendistribusikan kata-kata antara baris paragraf untuk menjaga bidang kanan paragraf |
| IsFormFillingMode | `4` | Mencoba menyebarkan kata-kata di ruang putih yang tersedia menggunakan lebar paragraf. Jika teks meluap, itu akan disembunyikan. |
| ShiftRestOfLine | `8` | (Default) Menggeser sisa baris sesuai dengan perubahan panjang teks, panjang baris mungkin berubah |

### Lihat Juga

* kelas [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)