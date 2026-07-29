---
title: "HtmlSaveOptions.ExplicitListOfSavedPages"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية HtmlSaveOptions. باستخدام هذه الخاصية يمكنك تحديد صراحةً الصفحات التي يجب تحويلها في المستند. يجب أن تكون أرقام الصفحات في هذه القائمة أرقامًا تبدأ من 1. أي يجب أخذ أرقام الصفحات الصالحة من النطاق 1...NumberOfPagesInConvertedDocument. ترتيب ظهور الصفحات في هذه القائمة لا يؤثر على ترتيبها في صفحات HTML الناتجة؛ في الصفحات الناتجة ستظهر دائمًا بالترتيب الذي توجد به في PDF المصدر. إذا كانت هذه القائمة null كما هو الافتراضي، فسيتم تحويل جميع الصفحات. إذا كان أي رقم صفحة في هذه القائمة خارج نطاق الصفحات الموجودة (amountOfPagesInDocument)، سيتم رمي استثناء."
type: docs
weight: 70
url: /ar/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages property

باستخدام هذه الخاصية يمكنك تحديد صراحةً الصفحات التي يجب تحويلها في المستند. يجب أن تكون أرقام الصفحات في هذه القائمة أرقامًا تبدأ من 1. أي أن أرقام الصفحات الصالحة يجب أن تُؤخذ من النطاق (1...[NumberOfPagesInConvertedDocument]). ترتيب ظهور الصفحات في هذه القائمة لا يؤثر على ترتيبها في صفحات HTML الناتجة - في الصفحات الناتجة ستظهر دائمًا بالترتيب الذي هي موجودة به في PDF المصدر. إذا كانت هذه القائمة null (كما هو افتراضي) فسيتم تحويل جميع الصفحات. إذا كان أي رقم صفحة في هذه القائمة خارج نطاق الصفحات الموجودة (1-[amountOfPagesInDocument]) سيتم رمي استثناء.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### انظر أيضًا

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


