---
title: "Delegate LoadOptions.ResourceLoadingStrategy"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kadang diperlukan untuk menghindari penggunaan pemuat internal sumber daya eksternal seperti gambar atau CSS dan menyediakan metode khusus yang akan mengambil sumber daya yang diminta dari suatu tempat. Misalnya selama penggunaan Aspose.Pdf di cloud akses langsung ke file yang direferensikan tidak memungkinkan dan beberapa kode khusus yang ditempatkan dalam metode khusus harus digunakan. Delegate ini mendefinisikan tanda tangan metode khusus tersebut"
type: docs
weight: 6300
url: /id/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

Kadang diperlukan untuk menghindari penggunaan pemuat internal sumber daya eksternal (seperti gambar atau CSS) dan menyediakan metode khusus, yang akan mengambil sumber daya yang diminta dari suatu tempat. Misalnya selama penggunaan Aspose.Pdf di cloud akses langsung ke file yang direferensikan tidak memungkinkan, dan beberapa kode khusus yang ditempatkan dalam metode khusus harus digunakan. Delegate ini mendefinisikan tanda tangan metode khusus tersebut.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceURI | String | URI Sumber Daya. |

### Nilai Kembalian

Objek ResourceLoadingResult.

### Lihat Juga

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


