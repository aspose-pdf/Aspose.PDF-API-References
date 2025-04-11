---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes enum. يمكن أن يحتوي PDF المحول على صور نقطية .png .jpeg إلخ. يحدد هذا التعداد طرق كيفية التعامل مع الصور النقطية أثناء تحويل PDF إلى HTML
type: docs
weight: 5720
url: /ar/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

يمكن أن يحتوي PDF المحول على صور نقطية (.png، *.jpeg إلخ) يحدد هذا التعداد طرق كيفية التعامل مع الصور النقطية أثناء تحويل PDF إلى HTML

```csharp
public enum RasterImagesSavingModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | لكل ملف نقطي متميز سيتم إنشاء صورة SVG مغلفة، وسيتم تضمين الصورة النقطية كسلاسل مشفرة بتنسيق Base64 في تلك الصورة SVG |
| AsExternalPngFilesReferencedViaSvg | `1` | سيتم وضع الصور النقطية المتميزة كملفات PNG ولكن سيتم الإشارة إليها من خلال صور SVG المغلفة، أي سيتم إنشاء ملف PNG واحد وملف SVG واحد لكل صورة نقطية، وستحتوي كل من هذه الصور SVG على روابط إلى ملف PNG ذي الصلة |
| AsEmbeddedPartsOfPngPageBackground | `2` | سيتم إنشاء ملف خلفية PNG كبير واحد لكل صفحة نتيجة. سيتم تضمين الصور النقطية في ذلك الملف وعرضها كأجزاء من تلك الصورة. لن يتم إنشاء ملفات PNG خارجية لكل صورة، سيكون هناك فقط ملف PNG واحد لكل صفحة في مجموعة ملفات نتيجة التحويل. |
| DontSave | `3` | لا تحفظ الصور لتنسيق التخطيط الثابت |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)