---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: أحيانًا يكون من الضروري تجنب استخدام المحمل الداخلي للموارد الخارجية مثل الصور أو CSS وتوفير طريقة مخصصة ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال، أثناء استخدام Aspose.Pdf في السحابة، يكون الوصول المباشر إلى الملفات المرجعية مستحيلًا، ويجب استخدام بعض الشيفرات المخصصة الموضوعة في طريقة خاصة. يحدد هذا المفوض توقيع هذه الطريقة المخصصة.
type: docs
weight: 6160
url: /ar/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

أحيانًا يكون من الضروري تجنب استخدام المحمل الداخلي للموارد الخارجية (مثل الصور أو CSS) وتوفير طريقة مخصصة، ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال، أثناء استخدام Aspose.Pdf في السحابة، يكون الوصول المباشر إلى الملفات المرجعية مستحيلًا، ويجب استخدام بعض الشيفرات المخصصة الموضوعة في طريقة خاصة. يحدد هذا المفوض توقيع هذه الطريقة المخصصة.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceURI | String | URI المورد. |

### Return Value

كائن ResourceLoadingResult.

### See Also

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)