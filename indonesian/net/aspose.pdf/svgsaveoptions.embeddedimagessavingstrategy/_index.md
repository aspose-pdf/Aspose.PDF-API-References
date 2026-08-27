---
title: "Delegasi SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Untuk properti tipe tersebut Anda dapat menetapkan delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan penyimpanan eksternal gambar yang diekstrak dari SVG yang dibuat dari PDF dan harus disimpan sebagai sumber eksternal selama konversi PDF ke HTML. Dalam kasus seperti itu pemrosesan seperti penyimpanan buatan sendiri ke aliran atau ke disk dapat dilakukan dalam kode khusus tersebut dan kode khusus itu harus mengembalikan path atau string lain tanpa tanda kutip yang kemudian akan dimasukkan ke dalam SVG yang dihasilkan menggantikan jalur asli yang diharapkan untuk sumber gambar tersebut. Dalam kasus ini semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disediakan karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau file itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri bukan dalam kode khusus, harap setel dalam kode khusus flag CustomProcessingCancelled pada variabel parameter imageSavingInfo. Itu memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber tersebut harus dilakukan di dalam konverter sebagaimana tidak ada kode khusus eksternal. merepresentasikan informasi tentang gambar yang disimpan yang dapat digunakan dalam kode khusus harus mengembalikan string yang merepresentasikan URL gambar yang akan dimasukkan ke dalam SVG"
type: docs
weight: 10420
url: /id/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegate

Untuk properti tipe tersebut Anda dapat menetapkan delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan penyimpanan eksternal gambar yang diekstrak dari SVG yang dibuat dari PDF dan harus disimpan sebagai sumber eksternal selama konversi PDF ke HTML. Dalam kasus seperti itu pemrosesan (seperti penyimpanan buatan sendiri ke aliran atau ke disk) dapat dilakukan dalam kode khusus tersebut dan kode khusus itu harus mengembalikan path (atau string lain tanpa tanda kutip) yang kemudian akan dimasukkan ke dalam SVG yang dihasilkan menggantikan jalur asli yang diharapkan untuk sumber gambar tersebut. Dalam kasus ini semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau file itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, harap setel dalam kode khusus flag 'CustomProcessingCancelled' dari variabel parameter 'imageSavingInfo'. Itu memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber tersebut harus dilakukan di dalam konverter sebagaimana tidak ada kode khusus eksternal. merepresentasikan informasi tentang gambar yang disimpan yang dapat digunakan dalam kode khusus harus mengembalikan string yang merepresentasikan URL gambar yang akan dimasukkan ke dalam SVG

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Lihat Juga

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


