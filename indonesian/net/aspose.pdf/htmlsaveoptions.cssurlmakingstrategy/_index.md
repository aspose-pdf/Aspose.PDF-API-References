---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Anda dapat menetapkan delegasi untuk properti ini yang dibuat dari metode kustom yang mengimplementasikan pembuatan URL dari CSS yang dirujuk dalam dokumen HTML yang dihasilkan. Misalnya, jika Anda ingin membuat CSS yang dirujuk dalam HTML misalnya sebagai otherPage.ASPXCssIDzjjkklj Maka strategi kustom tersebut harus mengembalikan otherPage.ASPXCssIDzjjkklj
type: docs
weight: 5600
url: /id/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## Delegasi HtmlSaveOptions.CssUrlMakingStrategy

Anda dapat menetapkan delegasi untuk properti ini yang dibuat dari metode kustom yang mengimplementasikan pembuatan URL dari CSS yang dirujuk dalam dokumen HTML yang dihasilkan. Misalnya, jika Anda ingin membuat CSS yang dirujuk dalam HTML misalnya sebagai "otherPage.ASPX?CssID=zjjkklj" Maka strategi kustom tersebut harus mengembalikan "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | mewakili sekumpulan data yang dapat digunakan untuk menghasilkan URL CSS |

### Nilai Kembali

harus mengembalikan string yang mewakili URL CSS atau template URL

### Lihat Juga

* kelas [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* kelas [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)