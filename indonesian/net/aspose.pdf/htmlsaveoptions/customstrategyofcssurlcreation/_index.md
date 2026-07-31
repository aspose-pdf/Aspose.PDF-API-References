---
title: "HtmlSaveOptions.CustomStrategyOfCssUrlCreation"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "HtmlSaveOptions field. Field ini dapat berisi metode khusus yang mengembalikan URL atau templat URL jika pembuatan multipage diaktifkan, lihat detail di bawah mengenai CSS yang harus dimasukkan ke dalam HTML hasil yang dihasilkan. Misalnya, jika Anda ingin konverter menempatkan URL tertentu alih-alih nama file CSS standar ke dalam CSS yang dihasilkan, maka Anda cukup membuat dan menempatkan ke properti ini metode yang menghasilkan URL yang diinginkan. Jika flag SplitCssIntoPages diatur, maka strategi khusus ini (jika ada) harus mengembalikan bukan URL CSS yang tepat tetapi string templat yang setelah substitusi placeholder dengan nomor halaman menggunakan fungsi string.Format di dalam konverter dapat diubah menjadi URL untuk CSS halaman tertentu. Contoh string yang diharapkan dalam kasus seperti itu adalah SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0"
type: docs
weight: 300
url: /id/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

Bidang ini dapat berisi metode khusus yang mengembalikan URL (atau templat URL jika generasi multi‑halaman diaktifkan – lihat detail di bawah) dari CSS subjek sebagaimana harus dimasukkan ke dalam HTML hasil yang dihasilkan. Misalnya, jika Anda ingin konverter menempatkan URL tertentu alih‑alih nama file CSS standar ke dalam CSS yang dihasilkan, maka Anda cukup membuat dan menempatkan ke properti ini metode yang menghasilkan URL yang diinginkan. Jika flag 'SplitCssIntoPages' diatur, maka strategi khusus ini (jika ada) harus mengembalikan bukan URL CSS yang tepat melainkan string templat yang (setelah penggantian placeholder dengan nomor halaman menggunakan fungsi string.Format() di dalam konverter) dapat diubah menjadi URL untuk URL CSS halaman tertentu. Contoh string yang diharapkan dikembalikan dalam kasus tersebut adalah: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Lihat Juga

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


