---
title: "Kelas SaveOptions.ResourceSavingInfo"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.SaveOptionsResourceSavingInfo. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file sumber eksternal yang terjadi selama konversi PDF ke format lain, misalnya HTML."
type: docs
weight: 10090
url: /id/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo class

Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file sumber eksternal yang terjadi selama konversi PDF ke format lain (mis. HTML)

```csharp
public class ResourceSavingInfo
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Ditentukan oleh konverter. Nama file yang diharapkan yang diteruskan dari konverter ke kode metode khusus. Dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan file tersebut. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Ditentukan oleh konverter. Mewakili konten biner dari file yang disimpan. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | bendera ini harus disetel ke "true" dalam kode khusus jika karena alasan tertentu file yang diusulkan harus diproses bukan dengan kode khusus melainkan dengan kode konverter itu sendiri dengan cara standar konverter. Jadi, pengaturannya disetel ke true berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri (dalam kedua konteks - untuk menyimpan di suatu tempat dan untuk penamaan dalam file referensi). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Ditentukan oleh konverter. Nama file yang diharapkan yang diteruskan dari konverter ke kode metode khusus. Dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan file tersebut. |

### Lihat Juga

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


