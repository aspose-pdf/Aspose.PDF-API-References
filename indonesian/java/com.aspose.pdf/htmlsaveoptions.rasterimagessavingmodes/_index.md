---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "PDF yang dikonversi dapat berisi gambar raster (.png, *.jpeg, dll.). Enum ini mendefinisikan metode bagaimana gambar raster dapat diproses selama konversi PDF ke HTML"
type: docs
weight: 2140
url: /id/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

PDF yang dikonversi dapat berisi gambar raster (.png, *.jpeg, dll.). Enum ini mendefinisikan metode bagaimana gambar raster dapat diproses selama konversi PDF ke HTML

## Fields

| Field | Deskripsi |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | Akan dihasilkan satu file latar belakang PNG besar untuk setiap halaman hasil. Gambar raster akan disematkan ke dalam file tersebut dan dirender sebagai wilayah gambar itu. Tidak ada file PNG eksternal untuk setiap gambar yang akan dihasilkan, hanya satu file PNG per halaman yang akan ada dalam set hasil konversi file. |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | gambar raster yang berbeda akan dipisahkan sebagai file PNG tetapi akan direferensikan melalui gambar SVG pembungkus, yaitu akan dihasilkan satu file PNG dan satu SVG untuk setiap gambar raster, dan setiap SVG tersebut akan berisi tautan ke file PNG yang relevan |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | untuk setiap file raster yang berbeda akan dihasilkan gambar SVG pembungkus, dan gambar raster akan disematkan sebagai string yang dikodekan Base64 ke dalam gambar SVG tersebut |
| [DontSave](#DontSave) | Jangan simpan gambar untuk Fixed Layout |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

Akan dihasilkan satu file latar belakang PNG besar untuk setiap halaman hasil. Gambar raster akan disematkan ke dalam file tersebut dan dirender sebagai wilayah gambar itu. Tidak ada file PNG eksternal untuk setiap gambar yang akan dihasilkan, hanya satu file PNG per halaman yang akan ada dalam set hasil konversi file.

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

gambar raster yang berbeda akan dipisahkan sebagai file PNG tetapi akan direferensikan melalui gambar SVG pembungkus, yaitu akan dihasilkan satu file PNG dan satu SVG untuk setiap gambar raster, dan setiap SVG tersebut akan berisi tautan ke file PNG yang relevan

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

untuk setiap file raster yang berbeda akan dihasilkan gambar SVG pembungkus, dan gambar raster akan disematkan sebagai string yang dikodekan Base64 ke dalam gambar SVG tersebut

### DontSave {#DontSave}
```
public static final int DontSave
```

Jangan simpan gambar untuk Fixed Layout
