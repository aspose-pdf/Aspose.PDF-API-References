---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.SaveOptionsResourceSavingInfo. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file sumber eksternal yang terjadi selama konversi PDF ke format lain, misalnya HTML
type: docs
weight: 9940
url: /id/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## Kelas SaveOptions.ResourceSavingInfo

Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file sumber eksternal yang terjadi selama konversi PDF ke format lain (misalnya HTML)

```csharp
public class ResourceSavingInfo
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Ditentukan oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode kustom. Dapat digunakan dalam kode kustom untuk memutuskan bagaimana memproses atau di mana menyimpan file tersebut |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Ditentukan oleh konverter. Mewakili konten biner dari file yang disimpan. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Bendera ini harus diatur ke "true" dalam kode kustom jika karena alasan tertentu file yang diusulkan harus diproses tidak dengan kode kustom tetapi dengan kode konverter itu sendiri dengan cara standar untuk konverter. Jadi, pengaturannya yang diatur ke true berarti bahwa kode kustom tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri (dalam kedua arti - untuk menyimpan di suatu tempat dan untuk penamaan dalam file yang dirujuk). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Ditentukan oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode kustom. Dapat digunakan dalam kode kustom untuk memutuskan bagaimana memproses atau di mana menyimpan file tersebut |

### Lihat Juga

* kelas [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)