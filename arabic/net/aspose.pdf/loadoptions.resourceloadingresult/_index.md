---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsResourceLoadingResult class. نتيجة تحميل المورد المخصص
type: docs
weight: 6150
url: /ar/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

نتيجة تحميل المورد المخصص

```csharp
public class ResourceLoadingResult
```

## Constructors

| Name | Description |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | ينشئ مثيلًا لنتيجة التحميل |

## Properties

| Name | Description |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | بيانات ثنائية تم تحميلها بواسطة محمل مخصص - يجب تعيينها بعد التحميل |

## Fields

| Name | Description |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | أحيانًا يكون ترميز المورد معروفًا بعد أو أثناء التحميل. في هذه الحالة، يمكن أن يوفر الكود المخصص المحول بهذه المعرفة عبر هذه المعلمة. يمكنك تركها فارغة إذا كان الترميز غير معروف أو لا يهم. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | أحيانًا يكون من المستحيل تحميل المورد المطلوب لسبب ما. عدم توفر المورد غالبًا لا يؤدي إلى تعطل التحويل ويمكن إنشاء مستند النتيجة على أي حال (لكن ربما بجودة أسوأ قليلاً، بدون صور، إلخ). إذا حدث استثناء أثناء التحميل، فقط قم بالتقاطه وضعه في هذه المعلمة - أحيانًا تكون تلك المعلومات مفيدة للمحول في عرض النتيجة. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | أحيانًا لأسباب معينة يجب ألا يحدث التحميل بواسطة الكود المخصص. في هذه الحالة، يرجى تعيين هذه العلامة كـ True. في هذه الحالة، سيحاول المحول استخدام محمل الموارد الافتراضي الداخلي للحصول على تلك النتيجة (كما يتصرف في الحالة عندما لا يتم توفير استراتيجية مخصصة). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | أحيانًا تكون المعرفة بنوع MIME للمورد المحمل مفيدة للمحول. يمكنك توفير نوع MIME (إذا كان معروفًا بعد التحميل) في هذه المعلمة. يرجى ترك المعلمة فارغة عندما يكون نوع MIME غير معروف أو ليس من الضروري توفيره. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)