---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: خاصية HtmlSaveOptions. باستخدام هذه الخاصية يمكنك تحديد الصفحات التي يجب تحويلها بشكل صريح. يجب أن تحتوي الصفحات في هذه القائمة على أرقام تبدأ من 1. أي أن الأرقام الصالحة للصفحات يجب أن تؤخذ من النطاق 1...NumberOfPagesInConvertedDocument. ترتيب ظهور الصفحات في هذه القائمة لا يؤثر على ترتيبها في صفحات HTML الناتجة - في الصفحات الناتجة ستظهر دائمًا بالترتيب الذي توجد به في ملف PDF المصدر. إذا كانت هذه القائمة فارغة ، فسيتم تحويل جميع الصفحات. إذا كان أي رقم صفحة في هذه القائمة خارج نطاق الصفحات الحالية  سيتم رمي استثناء.
type: docs
weight: 70
url: /ar/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## خاصية HtmlSaveOptions.ExplicitListOfSavedPages

باستخدام هذه الخاصية يمكنك تحديد الصفحات التي يجب تحويلها بشكل صريح. يجب أن تحتوي الصفحات في هذه القائمة على أرقام تبدأ من 1. أي أن الأرقام الصالحة للصفحات يجب أن تؤخذ من النطاق (1...[NumberOfPagesInConvertedDocument]). ترتيب ظهور الصفحات في هذه القائمة لا يؤثر على ترتيبها في صفحة HTML الناتجة - في الصفحات الناتجة ستظهر دائمًا بالترتيب الذي توجد به في ملف PDF المصدر. إذا كانت هذه القائمة فارغة (كما هو الحال بشكل افتراضي)، فسيتم تحويل جميع الصفحات. إذا كان أي رقم صفحة في هذه القائمة خارج نطاق الصفحات الحالية (1-[amountOfPagesInDocument]) سيتم رمي استثناء.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### انظر أيضًا

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)