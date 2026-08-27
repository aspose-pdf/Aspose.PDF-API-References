---
title: "مفوض LoadOptions.ResourceLoadingStrategy"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "في بعض الأحيان يكون من الضروري تجنب استخدام المحمل الداخلي للموارد الخارجية مثل الصور أو ملفات CSS وتوفير طريقة مخصصة ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال أثناء استخدام Aspose.Pdf في السحابة لا يمكن الوصول مباشرة إلى الملفات المشار إليها ويجب استخدام بعض الشيفرة المخصصة الموضوعة في طريقة خاصة. هذا المفوض يحدد توقيع تلك الطريقة المخصصة"
type: docs
weight: 6300
url: /ar/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

في بعض الأحيان يكون من الضروري تجنب استخدام المحمل الداخلي للموارد الخارجية (مثل الصور أو ملفات CSS) وتوفير طريقة مخصصة ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال أثناء استخدام Aspose.Pdf في السحابة لا يمكن الوصول مباشرة إلى الملفات المشار إليها، ويجب استخدام بعض الشيفرة المخصصة الموضوعة في طريقة خاصة. هذا المفوض يحدد توقيع تلك الطريقة المخصصة.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| resourceURI | String | معرف URI للموارد. |

### قيمة الإرجاع

كائن ResourceLoadingResult.

### انظر أيضًا

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


