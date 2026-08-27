---
title: "تعداد HtmlSaveOptions.RasterImagesSavingModes"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "تعداد Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes. يمكن أن يحتوي PDF المحول على صور نقطية .png .jpeg إلخ. يحدد هذا التعداد طرق معالجة الصور النقطية أثناء تحويل PDF إلى HTML"
type: docs
weight: 5850
url: /ar/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

يمكن أن يحتوي PDF المحول على صور نقطية (.png, *.jpeg إلخ). يحدد هذا التعداد طرق معالجة الصور النقطية أثناء تحويل PDF إلى HTML

```csharp
public enum RasterImagesSavingModes
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | لكل ملف نقطي مميز سيتم إنشاء صورة SVG مغلفة، وسيتم تضمين الصورة النقطية كسلاسل مشفرة Base64 داخل تلك الصورة SVG |
| AsExternalPngFilesReferencedViaSvg | `1` | ستُفصل الصور النقطية المميزة كملفات PNG ولكن سيتم الإشارة إليها عبر صور SVG مغلفة، أي سيتم إنشاء ملف PNG واحد وملف SVG واحد لكل صورة نقطية، وستحتوي كل من هذه الصور SVG على روابط إلى ملف PNG المناسب |
| AsEmbeddedPartsOfPngPageBackground | `2` | سيتم إنشاء ملف خلفية PNG كبير واحد لكل صفحة نتيجة. ستُدمج الصور النقطية في ذلك الملف وتُعرض كمنطقات من تلك الصورة. لن يتم إنشاء ملفات PNG خارجية لكل صورة، بل سيكون ملف PNG واحد فقط لكل صفحة موجودًا في مجموعة ملفات نتيجة التحويل. |
| DontSave | `3` | لا تقم بحفظ الصور لتخطيط ثابت |

### انظر أيضًا

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


