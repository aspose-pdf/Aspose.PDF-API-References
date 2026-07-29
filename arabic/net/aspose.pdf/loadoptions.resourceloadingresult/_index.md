---
title: "الفئة LoadOptions.ResourceLoadingResult"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.LoadOptionsResourceLoadingResult. نتيجة التحميل المخصص للمورد"
type: docs
weight: 6290
url: /ar/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

نتيجة التحميل المخصص للمورد

```csharp
public class ResourceLoadingResult
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | إنشاء نسخة من نتيجة التحميل |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | بيانات ثنائية تم تحميلها باستخدام محمل مخصص - يجب تعيينها بعد التحميل |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | في بعض الأحيان يكون ترميز المورد معروفًا بعد أو أثناء التحميل. في هذه الحالة يمكن للكود المخصص تزويد المحول بهذه المعلومة عبر هذا المعامل. يمكنك تركه null إذا كان الترميز غير معروف أو لا يهم. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | في بعض الأحيان يكون من المستحيل تحميل المورد المطلوب لسبب ما. عدم توفر المورد غالبًا لا يؤدي إلى تعطل التحويل ويمكن إنشاء مستند النتيجة على أي حال (ولكن ربما بجودة أقل قليلًا، بدون صور إلخ). إذا حدث استثناء أثناء التحميل، فقط امسكه وضعه في هذا المعامل - في بعض الأحيان تكون هذه المعلومة مفيدة للمحول في عرض النتيجة. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | في بعض الأحيان لأسباب معينة يجب ألا يحدث التحميل عبر كود مخصص. في هذه الحالة يرجى ضبط هذا العلم على True. سيسعى المحول لاستخدام محمل الموارد الافتراضي الداخلي للحصول على تلك النتيجة (كما يحدث عندما لا يتم توفير استراتيجية مخصصة). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | في بعض الأحيان تكون معرفة نوع MIME للمورد المحمل مفيدة للمحول. يمكنك توفير نوع MIME (إذا كان معروفًا بعد التحميل) في هذا المعامل. يرجى ترك المعامل يساوي null عندما يكون نوع MIME غير معروف أو لا يلزم توفيره. |

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


