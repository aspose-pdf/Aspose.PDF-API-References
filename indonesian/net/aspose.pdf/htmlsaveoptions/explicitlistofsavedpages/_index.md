---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: Properti HtmlSaveOptions. Dengan properti ini Anda dapat secara eksplisit mendefinisikan halaman mana dari dokumen yang harus dikonversi. Halaman dalam daftar ini harus memiliki nomor berbasis 1. Yaitu, nomor halaman yang valid harus diambil dari rentang 1...NumberOfPagesInConvertedDocument. Urutan kemunculan halaman dalam daftar ini tidak mempengaruhi urutan mereka dalam halaman HTML hasil - dalam halaman hasil, halaman selalu akan muncul dalam urutan di mana mereka ada dalam PDF sumber. Jika daftar ini null (seperti yang ada secara default), semua halaman akan dikonversi. Jika nomor halaman mana pun dari daftar ini keluar dari rentang halaman yang ada (1-[amountOfPagesInDocument]), pengecualian akan dilemparkan.
type: docs
weight: 70
url: /id/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## Properti HtmlSaveOptions.ExplicitListOfSavedPages

Dengan properti ini Anda dapat secara eksplisit mendefinisikan halaman mana dari dokumen yang harus dikonversi. Halaman dalam daftar ini harus memiliki nomor berbasis 1. Yaitu, nomor halaman yang valid harus diambil dari rentang (1...[NumberOfPagesInConvertedDocument]). Urutan kemunculan halaman dalam daftar ini tidak mempengaruhi urutan mereka dalam halaman HTML hasil - dalam halaman hasil, halaman selalu akan muncul dalam urutan di mana mereka ada dalam PDF sumber. Jika daftar ini null (seperti yang ada secara default), semua halaman akan dikonversi. Jika nomor halaman mana pun dari daftar ini keluar dari rentang halaman yang ada (1-[amountOfPagesInDocument]), pengecualian akan dilemparkan.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Lihat Juga

* kelas [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)