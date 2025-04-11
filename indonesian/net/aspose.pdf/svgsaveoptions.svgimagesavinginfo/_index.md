---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file gambar sumber eksternal selama konversi PDF ke HTML
type: docs
weight: 10260
url: /id/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## Kelas SvgSaveOptions.SvgImageSavingInfo

Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file gambar sumber eksternal selama konversi PDF ke HTML.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Diatur oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode kustom. Dapat digunakan dalam kode kustom untuk memutuskan bagaimana memproses atau di mana menyimpan file tersebut. |

## Field

| Nama | Deskripsi |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Diatur oleh konverter. Mewakili konten biner dari file yang disimpan. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Flag ini harus diatur ke "true" dalam kode kustom jika karena alasan tertentu file yang diusulkan harus diproses tidak dengan kode kustom tetapi dengan kode konverter itu sendiri dengan cara standar untuk konverter. Jadi, pengaturannya ke true berarti bahwa kode kustom tidak memproses file yang dirujuk dan konverter harus menangani sendiri (dalam kedua arti - untuk menyimpan di suatu tempat dan untuk penamaan dalam file yang dirujuk). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | Mewakili tipe gambar yang disimpan yang dirujuk dalam HTML. Diatur oleh konverter dan dapat digunakan dalam kode kustom untuk memutuskan apa yang harus dilakukan. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Diatur oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode kustom. Dapat digunakan dalam kode kustom untuk memutuskan bagaimana memproses atau di mana menyimpan file tersebut. |

### Lihat Juga

* kelas [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* kelas [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)