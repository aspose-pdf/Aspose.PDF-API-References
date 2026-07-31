---
title: "Enum HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes enum. Enum ini mengenumerasikan mode kemungkinan penyematan file yang direferensikan dalam HTML. Ini memungkinkan mengontrol apakah file yang direferensikan (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah."
type: docs
weight: 5840
url: /id/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

Enum ini mengenumerasikan mode kemungkinan penyematan file yang direferensikan dalam HTML. Ini memungkinkan mengontrol apakah file yang direferensikan (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah.

```csharp
public enum PartsEmbeddingModes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Memaksa semua file yang direferensikan (CSS, Gambar, Font) disematkan ke dalam markup HTML yang dihasilkan (yaitu ke dalam HTML itu sendiri). Pendekatan ini menghasilkan satu file HTML, tetapi ukuran total output menjadi lebih besar (karena penggunaan enkoding Base64 untuk biner) dan tidak semua peramban (terutama yang lama) dapat memproses biner yang disematkan ke dalam HTML dengan sukses. Namun hal ini memungkinkan memperoleh HTML yang berisi seluruh hasil, tanpa file tambahan. |
| EmbedCssOnly | `1` | Memaksa memisahkan semua file yang direferensikan kecuali CSS (Gambar dan Font). Artinya CSS akan disematkan ke dalam HTML hasil, sementara semua file lain yang direferensikan (Gambar dan Font) akan diproses sebagai bagian eksternal. Ini menghasilkan HTML yang cocok untuk berbagai peramban. |
| NoEmbedding | `2` | Memaksa memisahkan file yang direferensikan (CSS, Gambar, Font). Pendekatan ini menghasilkan sekumpulan file, tetapi ukuran total output menjadi lebih kecil (karena tidak ada enkoding Base64 untuk biner). Selain itu, pendekatan ini menghasilkan HTML yang cocok untuk berbagai peramban. |

### Lihat Juga

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


