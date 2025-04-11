---
title: RenderingOptions.AnalyzeFonts
second_title: Aspose.PDF for .NET API Reference
description: Properti RenderingOptions. Mengganti font sesuai kebutuhan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma penggantian font mengikuti langkah-langkah ini 1. Jika pengguna secara eksplisit mengatur properti DefaultFontName, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditentukan oleh pengguna, cari melalui font yang ditambahkan melalui FontRepository.Sources. 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font yang sesuai. Cobalah untuk menemukan dan menggunakan font ini dari sistem. 4. Sebagai cadangan, cari sistem untuk font apa pun yang mampu menampilkan karakter yang diperlukan.
type: docs
weight: 20
url: /id/net/aspose.pdf/renderingoptions/analyzefonts/
---
## Properti RenderingOptions.AnalyzeFonts

Mengganti font sesuai kebutuhan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma penggantian font mengikuti langkah-langkah ini: 1. Jika pengguna secara eksplisit mengatur properti DefaultFontName, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditentukan oleh pengguna, cari melalui font yang ditambahkan melalui !:FontRepository.Sources. 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font yang sesuai. Cobalah untuk menemukan dan menggunakan font ini dari sistem. 4. Sebagai cadangan, cari sistem untuk font apa pun yang mampu menampilkan karakter yang diperlukan.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Lihat Juga

* kelas [RenderingOptions](../)
* ruang nama [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)