---
title: "HtmlSaveOptions.ExplicitListOfSavedPages"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "HtmlSaveOptions property. Dengan properti ini Anda dapat secara eksplisit menentukan halaman mana dari dokumen yang harus dikonversi. Halaman dalam daftar ini harus memiliki nomor berbasis 1. Misalnya, nomor halaman yang valid harus diambil dari rentang 1...NumberOfPagesInConvertedDocument. Urutan munculnya halaman dalam daftar ini tidak memengaruhi urutan halaman HTML hasil; halaman hasil selalu ditampilkan dalam urutan yang sama dengan yang ada di PDF sumber. Jika daftar ini null (seperti default), semua halaman akan dikonversi. Jika ada nomor halaman dalam daftar ini yang berada di luar rentang halaman yang ada (jumlah halaman dalam dokumen), maka akan dilemparkan pengecualian."
type: docs
weight: 70
url: /id/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages property

Dengan properti ini Anda dapat secara eksplisit menentukan halaman mana dari dokumen yang harus dikonversi. Halaman dalam daftar ini harus memiliki nomor berbasis 1. Misalnya, nomor halaman yang valid harus diambil dari rentang (1...[NumberOfPagesInConvertedDocument]). Urutan munculnya halaman dalam daftar ini tidak memengaruhi urutan mereka dalam halaman HTML hasil - dalam halaman hasil selalu akan mengikuti urutan di mana mereka hadir dalam PDF sumber. Jika daftar ini null (seperti default), semua halaman akan dikonversi. Jika nomor halaman mana pun dalam daftar ini berada di luar rentang halaman yang ada (1-[amountOfPagesInDocument]) maka pengecualian akan dilempar.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Lihat Juga

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


