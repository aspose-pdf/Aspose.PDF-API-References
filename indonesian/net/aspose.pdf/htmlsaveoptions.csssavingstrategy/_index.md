---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Anda dapat menetapkan strategi kustom untuk properti ini yang mengimplementasikan pemrosesan atau/ dan penyimpanan salah satu bagian CSS yang dibuat selama konversi PDF ke HTML. Dalam hal ini, pemrosesan seperti menyimpan ke aliran atau disk harus dilakukan dalam kode kustom tersebut.
type: docs
weight: 5590
url: /id/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## Delegate HtmlSaveOptions.CssSavingStrategy

Anda dapat menetapkan strategi kustom untuk properti ini yang mengimplementasikan pemrosesan atau/ dan penyimpanan salah satu bagian CSS yang dibuat selama konversi PDF ke HTML. Dalam hal ini, pemrosesan (seperti menyimpan ke aliran atau disk) harus dilakukan dalam kode kustom tersebut.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | mewakili sekumpulan data yang dapat digunakan untuk penyimpanan bagian CSS yang disuplai |

### Lihat Juga

* kelas [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* kelas [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)