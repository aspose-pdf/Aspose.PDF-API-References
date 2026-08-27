---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Pada properti ini Anda dapat menetapkan delegate yang dibuat dari metode khusus yang mengimplementasikan pemrosesan sumber daya eksternal (Font atau Gambar) yang diekstrak dari PDF dan harus disimpan."
type: docs
weight: 2150
url: /id/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Untuk properti ini Anda dapat menetapkan delegate yang dibuat dari metode khusus yang mengimplementasikan pemrosesan sumber daya eksternal (Font atau Gambar) yang diekstrak dari PDF dan harus disimpan sebagai sumber daya eksternal selama konversi PDF ke HTML. Dalam kasus seperti itu pemrosesan (seperti menyimpan ke stream atau disk) dapat dilakukan dalam kode khusus tersebut dan kode khusus tersebut harus mengembalikan path (atau string lain tanpa tanda kutip) yang kemudian akan dimasukkan ke dalam HTML yang dihasilkan alih-alih path asli yang seharusnya ke sumber daya gambar tersebut. Dalam kasus seperti itu Semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan set dalam kode khusus flag 'CustomProcessingCancelled' dari variabel parameter 'resourceSavingInfo'. Itu memberi sinyal ke konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seolah-olah tidak ada kode khusus eksternal apa pun.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Metode yang dipanggil |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
Metode yang dipanggil
