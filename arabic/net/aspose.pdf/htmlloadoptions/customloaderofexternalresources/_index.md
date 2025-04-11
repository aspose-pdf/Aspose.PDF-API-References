---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: حقل HtmlLoadOptions. أحيانًا يكون من الضروري تجنب استخدام المحمل الداخلي للموارد الخارجية مثل الصور أو CSS وتوفير طريقة مخصصة للحصول على الموارد المطلوبة من مكان ما. على سبيل المثال، أثناء استخدام Aspose.PDF في السحابة، يكون الوصول المباشر إلى الملفات المرجعية مستحيلًا: في هذه الحالة، يجب استخدام بعض التعليمات البرمجية المخصصة الموضوعة في طريقة خاصة، ويجب تعيين المفوض الذي يشير إلى تلك الطريقة إلى هذه السمة.
type: docs
weight: 100
url: /ar/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## حقل HtmlLoadOptions.CustomLoaderOfExternalResources

أحيانًا يكون من الضروري تجنب استخدام المحمل الداخلي للموارد الخارجية (مثل الصور أو CSS) وتوفير طريقة مخصصة للحصول على الموارد المطلوبة من مكان ما. على سبيل المثال، أثناء استخدام Aspose.PDF في السحابة، يكون الوصول المباشر إلى الملفات المرجعية مستحيلًا: في هذه الحالة، يجب استخدام بعض التعليمات البرمجية المخصصة الموضوعة في طريقة خاصة، ويجب تعيين المفوض الذي يشير إلى تلك الطريقة إلى هذه السمة.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### انظر أيضًا

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* class [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)