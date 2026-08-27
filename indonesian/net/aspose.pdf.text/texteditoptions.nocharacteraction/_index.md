---
title: "Enum TextEditOptions.NoCharacterAction"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.Text.TextEditOptionsNoCharacterAction. Aksi yang dilakukan jika font tidak mengandung karakter yang diperlukan"
type: docs
weight: 11040
url: /id/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

Tindakan yang harus dilakukan jika font tidak mengandung karakter yang diperlukan

```csharp
public enum NoCharacterAction
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| ThrowException | `0` | Melempar pengecualian |
| UseStandardFont | `1` | Ganti font ke font standar yang mengandung karakter yang diperlukan |
| ReplaceAnyway | `2` | Ganti teks tetap tanpa substitusi font |
| ReplaceFonts | `3` | Mengganti font sesuai kebutuhan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma substitusi font mengikuti langkah-langkah berikut: 1. Jika pengguna secara eksplisit mengatur properti Font, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditetapkan pengguna, cari font yang ditambahkan melalui [`Sources`](../fontrepository/sources/). 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font yang sesuai. Coba temukan dan gunakan font tersebut dari sistem. 4. Sebagai cadangan, cari di sistem font apa pun yang mampu menampilkan karakter yang diperlukan. |
| UseCustomReplacementFont | `4` | Ganti font dengan font pengganti yang telah ditentukan |

### Lihat Juga

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


