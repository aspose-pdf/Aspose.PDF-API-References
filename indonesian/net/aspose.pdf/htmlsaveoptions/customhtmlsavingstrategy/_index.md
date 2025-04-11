---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Field HtmlSaveOptions. Hasil konversi dapat berisi satu atau beberapa halaman HTML. Anda dapat menetapkan delegasi untuk properti ini yang dibuat dari metode kustom yang mengimplementasikan pemrosesan satu halaman HTML (untuk secara akurat - markup-HTML, tanpa file terkait eksternal jika ada) yang dibuat selama konversi. Dalam hal ini, pemrosesan (seperti menyimpan HTML halaman dalam aliran atau disk) dapat dilakukan dalam kode kustom tersebut. Dalam hal ini, semua tindakan yang diperlukan untuk menyimpan halaman HTML harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode kustom, harap atur dalam kode kustom bendera 'CustomProcessingCancelled' dari variabel parameter 'htmlSavingInfo': itu akan memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber daya tersebut harus dilakukan di dalam konverter itu sendiri dengan cara yang sama seolah-olah tidak ada kode kustom eksternal untuk pemrosesan.
type: docs
weight: 270
url: /id/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## Field HtmlSaveOptions.CustomHtmlSavingStrategy

Hasil konversi dapat berisi satu atau beberapa halaman HTML. Anda dapat menetapkan delegasi untuk properti ini yang dibuat dari metode kustom yang mengimplementasikan pemrosesan satu halaman HTML (untuk secara akurat - markup-HTML, tanpa file terkait eksternal jika ada) yang dibuat selama konversi. Dalam hal ini, pemrosesan (seperti menyimpan HTML halaman dalam aliran atau disk) dapat dilakukan dalam kode kustom tersebut. Dalam hal ini, semua tindakan yang diperlukan untuk menyimpan halaman HTML harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode kustom, harap atur dalam kode kustom bendera 'CustomProcessingCancelled' dari variabel parameter 'htmlSavingInfo': itu akan memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber daya tersebut harus dilakukan di dalam konverter itu sendiri dengan cara yang sama seolah-olah tidak ada kode kustom eksternal untuk pemrosesan.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Lihat Juga

* delegasi [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* kelas [HtmlSaveOptions](../)
* ruang nama [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)