---
title: "RenderingOptions.AnalyzeFonts"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti RenderingOptions. Mengganti font sesuai kebutuhan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma substitusi font mengikuti langkah-langkah berikut: 1. Jika pengguna secara eksplisit mengatur properti DefaultFontName, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditetapkan pengguna, cari melalui font yang ditambahkan melalui FontRepository.Sources. 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font yang sesuai. Coba temukan dan gunakan font tersebut dari sistem. 4. Sebagai cadangan, cari di sistem font apa pun yang mampu menampilkan karakter yang diperlukan."
type: docs
weight: 20
url: /id/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts property

Mengganti font bila diperlukan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma substitusi font mengikuti langkah-langkah berikut: 1. Jika pengguna secara eksplisit mengatur properti DefaultFontName, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditetapkan pengguna, cari font yang ditambahkan melalui !:FontRepository.Sources. 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font yang sesuai. Coba temukan dan gunakan font tersebut dari sistem. 4. Sebagai cadangan, cari di sistem font apa pun yang dapat menampilkan karakter yang diperlukan.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Lihat Juga

* class [RenderingOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


