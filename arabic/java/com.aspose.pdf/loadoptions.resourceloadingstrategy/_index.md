---
title: "LoadOptions.ResourceLoadingStrategy"
linktitle: "LoadOptions.ResourceLoadingStrategy"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "أحيانًا يكون من الضروري تجنب استخدام المحمل الداخلي للموارد الخارجية (مثل الصور أو CSSes) وتوفير طريقة مخصصة ستحصل على الموارد المطلوبة من مكان ما."
type: docs
weight: 2830
url: /ar/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

في بعض الأحيان يكون من الضروري تجنب استخدام محمل الموارد الخارجية الداخلي (مثل الصور أو ملفات CSS) وتوفير طريقة مخصصة، ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال أثناء استخدام Aspose.PDf في السحابة لا يمكن الوصول مباشرة إلى الملفات المشار إليها، ويجب استخدام بعض الشيفرة المخصصة الموضوعة في طريقة خاصة. هذا المفوض يحدد توقيع تلك الطريقة المخصصة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [invoke](#invoke-java.lang.String-) |  |

### invoke {#invoke-java.lang.String-}
