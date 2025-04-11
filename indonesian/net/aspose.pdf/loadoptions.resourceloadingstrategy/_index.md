---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Terkadang perlu untuk menghindari penggunaan pemuat internal sumber daya eksternal seperti gambar atau CSS dan menyediakan metode kustom yang akan mendapatkan sumber daya yang diminta dari suatu tempat. Misalnya, selama penggunaan Aspose.Pdf di cloud, akses langsung ke file yang direferensikan tidak mungkin, dan beberapa kode kustom yang dimasukkan ke dalam metode khusus harus digunakan. Delegasi ini mendefinisikan tanda tangan dari metode kustom tersebut.
type: docs
weight: 6160
url: /id/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## Delegasi LoadOptions.ResourceLoadingStrategy

Terkadang perlu untuk menghindari penggunaan pemuat internal sumber daya eksternal (seperti gambar atau CSS) dan menyediakan metode kustom yang akan mendapatkan sumber daya yang diminta dari suatu tempat. Misalnya, selama penggunaan Aspose.Pdf di cloud, akses langsung ke file yang direferensikan tidak mungkin, dan beberapa kode kustom yang dimasukkan ke dalam metode khusus harus digunakan. Delegasi ini mendefinisikan tanda tangan dari metode kustom tersebut.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceURI | String | URI Sumber Daya. |

### Nilai Kembali

Objek ResourceLoadingResult.

### Lihat Juga

* kelas [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)