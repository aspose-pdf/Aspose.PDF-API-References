---
title: "HtmlSaveOptions.CustomHtmlSavingStrategy"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Bidang HtmlSaveOptions. Hasil konversi dapat berisi satu atau beberapa HTMLpages. Anda dapat menetapkan ke properti ini delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan satu HTMLpage agar menjadi markupHTML yang akurat tanpa file eksternal yang ditautkan jika ada yang dibuat selama konversi. Dalam kasus seperti itu, pemrosesan seperti penyimpanan halaman HTML dalam aliran atau disk dapat dilakukan dalam kode khusus tersebut. Dalam kasus tersebut semua tindakan yang diperlukan untuk menyimpan halaman HTML harus dilakukan dalam kode metode yang disediakan karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode khusus, harap atur dalam kode khusus bendera CustomProcessingCancelled pada variabel parameter htmlSavingInfo; itu akan memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter itu sendiri dengan cara yang sama seolah tidak ada kode khusus eksternal untuk pemrosesan."
type: docs
weight: 270
url: /id/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy field

Hasil konversi dapat berisi satu atau beberapa halaman HTML. Anda dapat menetapkan ke properti ini delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan satu halaman HTML (secara tepat - markup-HTML, tanpa file eksternal yang ditautkan jika ada) yang dibuat selama konversi. Dalam kasus seperti itu, pemrosesan (seperti menyimpan HTML halaman ke aliran atau disk) dapat dilakukan dalam kode khusus tersebut. Dalam kasus tersebut semua tindakan yang diperlukan untuk menyimpan halaman HTML harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan atur dalam kode khusus flag 'CustomProcessingCancelled' pada variabel parameter 'htmlSavingInfo': itu akan memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri dengan cara yang sama seolah-olah tidak ada kode khusus eksternal untuk pemrosesan.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Lihat Juga

* delegate [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


