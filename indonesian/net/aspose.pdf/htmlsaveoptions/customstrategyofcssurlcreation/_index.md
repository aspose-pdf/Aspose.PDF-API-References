---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: Field HtmlSaveOptions. Field ini dapat berisi metode kustom yang mengembalikan URL atau template URL jika pembuatan multipage diaktifkan - lihat rincian di bawah tentang subjek CSS seperti yang harus dimasukkan dalam hasil HTML yang dihasilkan. Misalnya, jika Anda ingin konverter memasukkan URL tertentu alih-alih nama file CSS standar ke dalam CSS yang dihasilkan, maka Anda hanya perlu membuat dan memasukkan metode ke dalam properti ini yang menghasilkan URL yang diinginkan. Jika flag 'SplitCssIntoPages' diatur, maka strategi kustom ini harus mengembalikan bukan URL CSS yang tepat tetapi string template yang dapat diselesaikan menjadi URL untuk CSS halaman ini atau itu.
type: docs
weight: 300
url: /id/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## Field HtmlSaveOptions.CustomStrategyOfCssUrlCreation

Field ini dapat berisi metode kustom yang mengembalikan URL (atau template URL jika pembuatan multipage diaktifkan - lihat rincian di bawah) dari subjek CSS seperti yang harus dimasukkan dalam hasil HTML yang dihasilkan. Misalnya, jika Anda ingin konverter memasukkan URL tertentu alih-alih nama file CSS standar ke dalam CSS yang dihasilkan, maka Anda hanya perlu membuat dan memasukkan metode ke dalam properti ini yang menghasilkan URL yang diinginkan. Jika flag 'SplitCssIntoPages' diatur, maka strategi kustom ini (jika ada) harus mengembalikan bukan URL CSS yang tepat tetapi string template yang (setelah penggantian placeholder dengan nomor halaman menggunakan fungsi string.Format() di dalam konverter) dapat diselesaikan menjadi URL untuk CSS halaman ini atau itu. Contoh string yang diharapkan dikembalikan dalam kasus seperti itu adalah: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}'

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Lihat Juga

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)