---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsRasterImagesSavingModes Aspose.Pdf. PDF yang dikonversi dapat berisi gambar raster.png .jpeg dll. Enum ini mendefinisikan metode bagaimana gambar raster dapat ditangani selama konversi PDF ke HTML
type: docs
weight: 5720
url: /id/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## Enumerasi HtmlSaveOptions.RasterImagesSavingModes

PDF yang dikonversi dapat berisi gambar raster(.png, *.jpeg dll.) Enum ini mendefinisikan metode bagaimana gambar raster dapat ditangani selama konversi PDF ke HTML

```csharp
public enum RasterImagesSavingModes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | untuk setiap file raster yang berbeda akan dihasilkan gambar SVG pembungkus, dan gambar raster akan disematkan sebagai string yang dikodekan Base64 ke dalam gambar SVG tersebut |
| AsExternalPngFilesReferencedViaSvg | `1` | gambar raster yang berbeda akan dipisahkan sebagai file PNG tetapi akan dirujuk melalui gambar SVG pembungkus, yaitu akan dihasilkan satu file PNG dan satu SVG untuk setiap gambar raster, dan masing-masing SVG tersebut akan berisi tautan ke file PNG yang relevan |
| AsEmbeddedPartsOfPngPageBackground | `2` | Akan dihasilkan satu file latar belakang PNG besar untuk setiap halaman hasil. Gambar raster akan disematkan ke dalam file tersebut dan dirender sebagai wilayah dari gambar tersebut. Tidak akan dihasilkan file PNG eksternal untuk setiap gambar, hanya satu file PNG per halaman yang akan ada dalam hasil konversi set file. |
| DontSave | `3` | Jangan simpan gambar untuk Tata Letak Tetap |

### Lihat Juga

* kelas [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)