---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "قد يحتوي ملف PDF المحوّل على صور نقطية (.png، *.jpeg وغيرها). هذا التعداد يحدد طرق معالجة الصور النقطية أثناء تحويل PDF إلى HTML."
type: docs
weight: 2140
url: /ar/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

قد يحتوي ملف PDF المحوّل على صور نقطية (.png، *.jpeg وغيرها). هذا التعداد يحدد طرق معالجة الصور النقطية أثناء تحويل PDF إلى HTML.

## الحقول

| حقل | الوصف |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | سيتم إنشاء ملف خلفية PNG كبير واحد لكل صفحة نتيجة. سيتم تضمين صور Raster في ذلك الملف وعرضها كمنطقات من تلك الصورة. لن يتم إنشاء ملفات PNG خارجية لكل صورة، بل سيكون ملف PNG واحد فقط لكل صفحة موجودًا في مجموعة نتائج التحويل من الملفات. |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | ستُوضع صور Raster المتميزة كملفات PNG منفصلة ولكن سيتم الإشارة إليها عبر تغليفها بصور SVG، أي سيتم إنشاء ملف PNG واحد وملف SVG واحد لكل صورة Raster، وستحتوي كل من هذه ملفات SVG على روابط إلى ملف PNG المناسب. |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | لكل ملف Raster مميز سيتم إنشاء صورة SVG مغلفة، وستُضمّن صورة Raster كسلاسل مشفّرة Base64 داخل تلك الصورة SVG. |
| [DontSave](#DontSave) | لا تقم بحفظ الصور لتنسيق Fixed Layout |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

سيتم إنشاء ملف خلفية PNG كبير واحد لكل صفحة نتيجة. سيتم تضمين صور Raster في ذلك الملف وعرضها كمنطقات من تلك الصورة. لن يتم إنشاء ملفات PNG خارجية لكل صورة، بل سيكون ملف PNG واحد فقط لكل صفحة موجودًا في مجموعة نتائج التحويل من الملفات.

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

ستُوضع صور Raster المتميزة كملفات PNG منفصلة ولكن سيتم الإشارة إليها عبر تغليفها بصور SVG، أي سيتم إنشاء ملف PNG واحد وملف SVG واحد لكل صورة Raster، وستحتوي كل من هذه ملفات SVG على روابط إلى ملف PNG المناسب.

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

لكل ملف Raster مميز سيتم إنشاء صورة SVG مغلفة، وستُضمّن صورة Raster كسلاسل مشفّرة Base64 داخل تلك الصورة SVG.

### DontSave {#DontSave}
```
public static final int DontSave
```

لا تقم بحفظ الصور لتنسيق Fixed Layout
