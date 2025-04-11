---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Untuk properti tipe tersebut Anda dapat menetapkan delegasi yang dibuat dari metode kustom yang mengimplementasikan pemrosesan penyimpanan eksternal gambar yang diekstrak dari SVG yang dibuat dari PDF dan harus disimpan sebagai sumber eksternal selama konversi PDF ke HTML. Dalam hal ini, pemrosesan seperti penyimpanan buatan sendiri ke dalam aliran atau di disk dapat dilakukan dalam kode kustom tersebut dan kode kustom itu harus mengembalikan path (atau string lain tanpa tanda kutip) yang kemudian akan dimasukkan ke dalam SVG yang dihasilkan sebagai pengganti path asli yang seharusnya untuk sumber gambar tersebut. Dalam hal ini, semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disuplai, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau itu karena suatu alasan harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode kustom, silakan atur dalam kode kustom bendera 'CustomProcessingCancelled' dari variabel parameter 'imageSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber tersebut harus dilakukan di dalam konverter itu sendiri seolah-olah tidak ada kode kustom eksternal. . mewakili informasi tentang gambar yang disimpan yang dapat digunakan dalam kode kustom harus mengembalikan string yang mewakili URL gambar yang akan dimasukkan ke dalam SVG
type: docs
weight: 10240
url: /id/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## Delegasi SvgSaveOptions.EmbeddedImagesSavingStrategy

Untuk properti tipe tersebut Anda dapat menetapkan delegasi yang dibuat dari metode kustom yang mengimplementasikan pemrosesan penyimpanan eksternal gambar yang diekstrak dari SVG yang dibuat dari PDF dan harus disimpan sebagai sumber eksternal selama konversi PDF ke HTML. Dalam hal ini, pemrosesan (seperti penyimpanan buatan sendiri ke dalam aliran atau di disk) dapat dilakukan dalam kode kustom tersebut dan kode kustom itu harus mengembalikan path (atau string lain tanpa tanda kutip) yang kemudian akan dimasukkan ke dalam SVG yang dihasilkan sebagai pengganti path asli yang seharusnya untuk sumber gambar tersebut. Dalam hal ini, semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disuplai, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau itu karena suatu alasan harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode kustom, silakan atur dalam kode kustom bendera 'CustomProcessingCancelled' dari variabel parameter 'imageSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber tersebut harus dilakukan di dalam konverter itu sendiri seolah-olah tidak ada kode kustom eksternal. . mewakili informasi tentang gambar yang disimpan yang dapat digunakan dalam kode kustom harus mengembalikan string yang mewakili URL gambar yang akan dimasukkan ke dalam SVG

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Lihat Juga

* kelas [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* kelas [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)