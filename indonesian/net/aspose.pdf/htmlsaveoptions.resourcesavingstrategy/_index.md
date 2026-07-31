---
title: "Delegasi HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Untuk properti ini Anda dapat menetapkan delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan sumber daya eksternal resourceFont atau Image yang diekstrak dari PDF dan harus disimpan sebagai sumber daya eksternal selama konversi PDF ke HTML. Dalam kasus seperti itu, pemrosesan seperti penyimpanan ke stream atau disk dapat dilakukan dalam kode khusus tersebut dan kode khusus itu harus mengembalikan path atau string lain tanpa tanda kutip yang kemudian akan dimasukkan ke dalam HTML yang dihasilkan menggantikan path asli yang seharusnya ke sumber daya gambar tersebut. Dalam kasus ini semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disediakan karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri bukan dalam kode khusus, silakan atur dalam kode khusus flag CustomProcessingCancelled dari variabel parameter resourceSavingInfo. Itu memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seolah-olah tidak ada kode khusus eksternal apa pun."
type: docs
weight: 5860
url: /id/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

Untuk properti ini Anda dapat menetapkan delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan sumber daya eksternal (Font atau Image) yang diekstrak dari PDF dan harus disimpan sebagai sumber daya eksternal selama konversi PDF ke HTML. Dalam kasus seperti itu, pemrosesan (seperti penyimpanan ke stream atau disk) dapat dilakukan dalam kode khusus tersebut dan kode khusus itu harus mengembalikan path (atau string lain tanpa tanda kutip) yang kemudian akan dimasukkan ke dalam HTML yang dihasilkan menggantikan path asli yang seharusnya ke sumber daya gambar tersebut. Dalam kasus ini semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan atur dalam kode khusus flag 'CustomProcessingCancelled' dari variabel parameter 'resourceSavingInfo'. Itu memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seolah-olah tidak ada **any external custom code**.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | mewakili sekumpulan data untuk penyimpanan sumber daya |

### Nilai Kembalian

harus mengembalikan URL ke sumber daya yang disimpan yang akan digunakan selama pembuatan HTML

### Lihat Juga

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


