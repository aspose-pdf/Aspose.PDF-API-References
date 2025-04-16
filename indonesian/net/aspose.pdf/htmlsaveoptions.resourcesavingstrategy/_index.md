---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Pada properti ini Anda dapat menetapkan delegasi yang dibuat dari metode kustom yang mengimplementasikan pemrosesan sumber daya eksternal yang diekstrak dari PDF dan harus disimpan sebagai sumber daya eksternal selama konversi PDF ke HTML. Dalam hal ini, pemrosesan seperti menyimpan dalam stream atau disk dapat dilakukan dalam kode kustom tersebut dan kode kustom itu harus mengembalikan path yang akan dimasukkan ke dalam HTML yang dihasilkan sebagai pengganti path asli yang seharusnya untuk sumber daya gambar tersebut. Dalam hal ini, semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disuplai, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau itu karena suatu alasan harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode kustom, silakan atur dalam kode kustom bendera 'CustomProcessingCancelled' dari variabel parameter 'resourceSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber daya tersebut harus dilakukan di dalam konverter itu sendiri seolah-olah tidak ada kode kustom eksternal.
type: docs
weight: 5730
url: /id/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## Delegate HtmlSaveOptions.ResourceSavingStrategy

Pada properti ini Anda dapat menetapkan delegasi yang dibuat dari metode kustom yang mengimplementasikan pemrosesan sumber daya eksternal (Font atau Gambar) yang diekstrak dari PDF dan harus disimpan sebagai sumber daya eksternal selama konversi PDF ke HTML. Dalam hal ini, pemrosesan (seperti menyimpan dalam stream atau disk) dapat dilakukan dalam kode kustom tersebut dan kode kustom itu harus mengembalikan path (atau string lain tanpa tanda kutip) yang akan dimasukkan ke dalam HTML yang dihasilkan sebagai pengganti path asli yang seharusnya untuk sumber daya gambar tersebut. Dalam hal ini, semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disuplai, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau itu karena suatu alasan harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode kustom, silakan atur dalam kode kustom bendera 'CustomProcessingCancelled' dari variabel parameter 'resourceSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber daya tersebut harus dilakukan di dalam konverter itu sendiri seolah-olah tidak ada kode kustom eksternal.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | mewakili kumpulan data untuk penyimpanan sumber daya |

### Nilai Kembali

harus mengembalikan URL ke sumber daya yang disimpan yang akan digunakan selama pembuatan HTML

### Lihat Juga

* kelas [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* kelas [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)