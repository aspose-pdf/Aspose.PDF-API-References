---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Untuk properti tipe tersebut Anda dapat menetapkan delegate yang dibuat dari metode kustom yang mengimplementasikan pemrosesan penyimpanan eksternal gambar yang diekstrak dari SVG yang dibuat dari PDF."
type: docs
weight: 4730
url: /id/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

Untuk properti tipe tersebut Anda dapat menetapkan delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan penyimpanan eksternal gambar yang diekstrak dari SVG yang dibuat dari PDF dan harus disimpan sebagai sumber daya eksternal selama konversi PDF ke HTML. Dalam kasus ini pemrosesan (seperti penyimpanan buatan sendiri ke aliran atau ke disk) dapat dilakukan dalam kode khusus tersebut dan kode khusus itu harus mengembalikan jalur (atau string lain tanpa tanda kutip) yang kemudian akan dimasukkan ke dalam SVG yang dihasilkan menggantikan jalur asli yang seharusnya menuju sumber daya gambar tersebut. Dalam kasus ini semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan set dalam kode khusus flag 'CustomProcessingCancelled' dari variabel parameter 'imageSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seolah-olah tidak ada kode khusus eksternal apa pun.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
