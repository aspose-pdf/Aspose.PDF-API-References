---
title: "Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Hasil konversi dapat berisi satu atau beberapa HTMLpages yang juga dapat merujuk ke file eksternal seperti gambar atau font. Anda dapat menetapkan delegasi ke properti ini yang dibuat dari metode khusus yang mengimplementasikan pemrosesan HTMLpageHTML yang dihasilkan sendiri yang dibuat selama konversi. Dalam kasus seperti itu, pemrosesan seperti menyimpan ke stream atau disk dapat dilakukan dalam kode khusus tersebut. Dalam kasus seperti itu Semua tindakan yang diperlukan untuk menyimpan markup halaman HTML harus dilakukan dalam kode metode yang disediakan karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri bukan dalam kode khusus, silakan atur flag CustomProcessingCancelled pada variabel parameter htmlSavingInfo dalam kode khusus; itu memberi sinyal ke konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri dengan cara yang sama seolah tidak ada kode penyimpanan khusus eksternal."
type: docs
weight: 5810
url: /id/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

Hasil konversi dapat berisi satu atau beberapa HTML-pages (yang juga dapat merujuk ke file eksternal seperti gambar atau font). Anda dapat menetapkan delegasi ke properti ini yang dibuat dari metode khusus yang mengimplementasikan pemrosesan HTML-page (HTML itu sendiri) yang dibuat selama konversi. Dalam kasus seperti itu, pemrosesan (seperti menyimpan ke stream atau disk) dapat dilakukan dalam kode khusus tersebut. Dalam kasus seperti itu Semua tindakan yang diperlukan untuk menyimpan markup halaman HTML harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan atur flag 'CustomProcessingCancelled' pada variabel parameter 'htmlSavingInfo'; itu memberi sinyal ke konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri dengan cara yang sama seolah tidak ada kode penyimpanan khusus eksternal.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | menyatakan data yang dapat digunakan untuk menyimpan atau memproses halaman HTML yang disediakan |

### Lihat Juga

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


