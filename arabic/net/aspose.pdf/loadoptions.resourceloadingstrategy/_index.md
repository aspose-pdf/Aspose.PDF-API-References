---
title: LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF لمرجع .NET API
description: في بعض الأحيان يكون من الضروري تجنب استخدام أداة التحميل الداخلية للموارد الخارجية مثل الصور أو CSSes وطريقة العرض المخصصة  والتي ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال أثناء الاستخدام لـ Aspose.Pdf في الوصول المباشر السحابي إلى الملفات المرجعية مستحيل  ويجب استخدام بعض التعليمات البرمجية المخصصة التي تم وضعها في طريقة special .
type: docs
weight: 3990
url: /ar/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

في بعض الأحيان يكون من الضروري تجنب استخدام أداة التحميل الداخلية للموارد الخارجية (مثل الصور أو CSSes) وطريقة العرض المخصصة ، والتي ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال أثناء الاستخدام لـ Aspose.Pdf في الوصول المباشر السحابي إلى الملفات المرجعية مستحيل ، ويجب استخدام بعض التعليمات البرمجية المخصصة التي تم وضعها في طريقة special .

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| resourceURI | String | المورد URI. |

### قيمة الإرجاع

كائن ResourceLoadingResult.

### أنظر أيضا

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult)
* class [LoadOptions](../loadoptions)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
