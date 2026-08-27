---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Hasil konversi dapat berisi satu atau beberapa halaman HTML (yang juga dapat mereferensikan file eksternal seperti gambar atau font). Anda dapat menetapkan delegasi yang dibuat dari properti ini."
type: docs
weight: 2110
url: /id/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Hasil konversi dapat berisi satu atau beberapa halaman HTML (yang juga dapat merujuk ke file eksternal seperti gambar atau font). Anda dapat menetapkan delegasi yang dibuat dari metode khusus ke properti ini yang mengimplementasikan pemrosesan halaman HTML yang dihasilkan (HTML itu sendiri) yang dibuat selama konversi. Dalam kasus tersebut, pemrosesan (seperti penyimpanan ke aliran atau disk) dapat dilakukan dalam kode khusus tersebut. Semua tindakan yang diperlukan untuk menyimpan markup halaman HTML harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan atur flag 'CustomProcessingCancelled' pada variabel parameter 'htmlSavingInfo' dalam kode khusus: itu memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seperti seolah-olah tidak ada kode penyimpanan khusus eksternal.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Metode beginInvoke internal |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Metode endInvoke internal |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Metode yang dipanggil |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
Metode beginInvoke internal

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
Metode endInvoke internal

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
Metode yang dipanggil
