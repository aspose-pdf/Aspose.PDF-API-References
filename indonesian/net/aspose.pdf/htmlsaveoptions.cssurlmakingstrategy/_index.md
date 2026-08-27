---
title: "Delegasi HtmlSaveOptions.CssUrlMakingStrategy"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Anda dapat menetapkan delegasi yang dibuat dari metode khusus yang mengimplementasikan pembuatan URL CSS yang direferensikan dalam dokumen HTML yang dihasilkan ke properti ini. Misalnya, jika Anda ingin membuat CSS yang direferensikan dalam HTML misalnya sebagai otherPage.ASPXCssIDzjjkklj, maka strategi khusus tersebut harus mengembalikan otherPage.ASPXCssIDzjjkklj"
type: docs
weight: 5730
url: /id/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

Anda dapat menetapkan delegasi yang dibuat dari metode khusus yang mengimplementasikan pembuatan URL CSS yang direferensikan dalam dokumen HTML yang dihasilkan ke properti ini. Misalnya, jika Anda ingin membuat CSS yang direferensikan dalam HTML misalnya sebagai "otherPage.ASPX?CssID=zjjkklj", maka strategi khusus tersebut harus mengembalikan "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | mewakili sekumpulan data yang dapat digunakan untuk menghasilkan URL CSS |

### Nilai Kembalian

harus mengembalikan string yang mewakili URL CSS atau templat URL

### Lihat Juga

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


