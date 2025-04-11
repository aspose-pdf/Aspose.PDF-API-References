---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Text.TextEditOptionsNoCharacterAction. Tindakan yang dilakukan jika font tidak mengandung karakter yang diperlukan
type: docs
weight: 10860
url: /id/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## Enumerasi TextEditOptions.NoCharacterAction

Tindakan yang dilakukan jika font tidak mengandung karakter yang diperlukan

```csharp
public enum NoCharacterAction
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| ThrowException | `0` | Lempar pengecualian |
| UseStandardFont | `1` | Ganti font dengan font standar yang mengandung karakter yang diperlukan |
| ReplaceAnyway | `2` | Ganti teks tanpa penggantian font |
| ReplaceFonts | `3` | Mengganti font sesuai kebutuhan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma penggantian font mengikuti langkah-langkah ini: 1. Jika pengguna secara eksplisit mengatur properti Font, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditentukan oleh pengguna, cari melalui font yang ditambahkan melalui [`Sources`](../fontrepository/sources/). 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font sesuai. Cobalah untuk menemukan dan menggunakan font ini dari sistem. 4. Sebagai cadangan, cari sistem untuk font yang mampu menampilkan karakter yang diperlukan. |
| UseCustomReplacementFont | `4` | Ganti font dengan font pengganti yang ditentukan |

### Lihat Juga

* kelas [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)