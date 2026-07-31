---
title: "Enum HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes enum. PDF yang dikonversi dapat berisi gambar raster .png .jpeg dll. Enum ini mendefinisikan metode bagaimana gambar raster dapat ditangani selama konversi PDF ke HTML"
type: docs
weight: 5850
url: /id/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

PDF yang dikonversi dapat berisi gambar raster (.png, *.jpeg dll.) Enum ini mendefinisikan metode bagaimana gambar raster dapat ditangani selama konversi PDF ke HTML

```csharp
public enum RasterImagesSavingModes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | untuk setiap file raster yang berbeda akan dihasilkan gambar SVG pembungkus, dan gambar raster akan disematkan sebagai string yang dienkode Base64 ke dalam gambar SVG tersebut |
| AsExternalPngFilesReferencedViaSvg | `1` | gambar raster yang berbeda akan dipisahkan sebagai file PNG tetapi akan direferensikan melalui gambar SVG pembungkus, yaitu akan dihasilkan satu file PNG dan satu SVG untuk setiap gambar raster, dan setiap SVG tersebut akan berisi tautan ke file PNG yang relevan |
| AsEmbeddedPartsOfPngPageBackground | `2` | Akan dihasilkan satu file latar belakang PNG besar untuk setiap halaman hasil. Gambar raster akan disematkan ke dalam file tersebut dan dirender sebagai wilayah gambar tersebut. Tidak ada file PNG eksternal untuk setiap gambar yang akan dihasilkan, hanya satu file PNG per halaman yang akan ada dalam set hasil konversi file. |
| DontSave | `3` | Jangan simpan gambar untuk Tata Letak Tetap |

### Lihat Juga

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


