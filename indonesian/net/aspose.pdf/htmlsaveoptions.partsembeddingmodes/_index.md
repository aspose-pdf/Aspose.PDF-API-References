---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsPartsEmbeddingModes Aspose.Pdf. Enum ini mencantumkan kemungkinan mode penyematan file yang dirujuk dalam HTML. Ini memungkinkan untuk mengontrol apakah file yang dirujuk akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah.
type: docs
weight: 5710
url: /id/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## Enumerasi HtmlSaveOptions.PartsEmbeddingModes

Enum ini mencantumkan kemungkinan mode penyematan file yang dirujuk dalam HTML. Ini memungkinkan untuk mengontrol apakah file yang dirujuk (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah.

```csharp
public enum PartsEmbeddingModes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Memaksa menyematkan semua file yang dirujuk (CSS, Gambar, Font) ke dalam markup HTML yang dihasilkan (yaitu ke dalam HTML itu sendiri). Pendekatan ini menghasilkan satu file HTML, tetapi ukuran total output menjadi lebih besar (karena encoding Base64 dari biner digunakan) dan tidak semua browser (terutama yang lama) berhasil memproses biner yang disematkan ke dalam HTML. Namun, ini memungkinkan untuk mendapatkan HTML yang berisi seluruh hasil, tanpa file tambahan. |
| EmbedCssOnly | `1` | Memaksa untuk memisahkan semua file yang dirujuk kecuali CSS (Gambar dan Font). Yaitu, CSS akan disematkan ke dalam HTML hasil, dan semua file yang dirujuk lainnya (Gambar dan Font) akan diproses sebagai bagian eksternal. Ini menghasilkan HTML yang cocok untuk berbagai set browser. |
| NoEmbedding | `2` | Memaksa untuk memisahkan file yang dirujuk (CSS, Gambar, Font). Pendekatan ini menghasilkan serangkaian file, tetapi ukuran total output menjadi lebih kecil (karena tidak ada encoding Base64 dari biner yang digunakan). Pendekatan seperti ini juga menghasilkan HTML yang cocok untuk berbagai set browser. |

### Lihat Juga

* kelas [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)