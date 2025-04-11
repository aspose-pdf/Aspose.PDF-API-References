---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Hasil konversi dapat berisi satu atau beberapa halaman HTML yang juga dapat merujuk ke file eksternal seperti gambar atau font. Anda dapat menetapkan properti ini ke delegasi yang dibuat dari metode kustom yang mengimplementasikan pemrosesan halaman HTML yang dihasilkan selama konversi. Dalam hal ini, pemrosesan seperti menyimpan dalam aliran atau disk dapat dilakukan dalam kode kustom tersebut. Dalam hal ini, semua tindakan yang diperlukan untuk menyimpan markup halaman HTML harus dilakukan dalam kode metode yang disuplai karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu harus dilakukan oleh kode konverter itu sendiri dan bukan dalam kode kustom, harap atur dalam kode kustom bendera CustomProcessingCancelled dari variabel parameter htmlSavingInfo, yang memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber daya tersebut harus dilakukan dalam konverter itu sendiri dengan cara yang sama seolah-olah tidak ada kode penyimpanan kustom eksternal.
type: docs
weight: 5680
url: /id/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
| --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | mewakili data yang dapat digunakan untuk menyimpan atau memproses halaman HTML yang disuplai |

### Lihat Juga

* kelas [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* kelas [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)