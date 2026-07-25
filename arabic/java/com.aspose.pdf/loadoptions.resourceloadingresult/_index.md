---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "نتيجة التحميل المخصص للمورد"
type: docs
weight: 2820
url: /ar/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

نتيجة التحميل المخصص للمورد

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | ينشئ نسخة من نتيجة التحميل |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getData](#getData--) | البيانات الثنائية التي تم تحميلها باستخدام محمل مخصص - يجب تعيينها بعد التحميل |
| [getEncodingIfKnown](#getEncodingIfKnown--) | أحيانًا يكون ترميز المورد معروفًا بعد أو أثناء التحميل. في هذه الحالة يمكن للكود المخصص أن يزود المحول بهذه المعلومة عبر هذه المعلمة. يمكنك ترك القيمة null في هذه المعلمة إذا كان الترميز غير معروف أو لا يهم. |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | أحيانًا يكون من المستحيل تحميل المورد المطلوب لسبب ما. عدم توفر المورد غالبًا لا يؤدي إلى تعطل التحويلات ويمكن إنشاء مستند النتيجة على أي حال (ولكن ربما بجودة أقل قليلًا، بدون صور إلخ). إذا حدث استثناء أثناء التحميل، فقط امسكه وضعه في هذه المعلمة - أحيانًا تكون هذه المعلومات مفيدة للمحول في عرض النتيجة. |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | أحيانًا تكون معرفة نوع MIME للمورد المحمل مفيدة للمحول. يمكنك توفير نوع MIME (إذا كان معروفًا بعد التحميل) في هذه المعلمة. يرجى ترك المعلمة مساوية لـ null عندما يكون نوع MIME غير معروف أو لا يلزم توفيره. |
| [isLoadingCancelled](#isLoadingCancelled--) | أحيانًا لأسباب معينة يجب ألا يحدث التحميل عبر كود مخصص. في هذه الحالة يرجى تعيين هذه العلامة إلى True. في هذه الحالة سيحاول المحول استخدام محمل الموارد الافتراضي الداخلي للحصول على تلك النتيجة (كما يحدث عندما لا يتم توفير استراتيجية مخصصة). |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | أحيانًا يكون ترميز المورد معروفًا بعد أو أثناء التحميل. في هذه الحالة يمكن للكود المخصص أن يزود المحول بهذه المعلومة عبر هذه المعلمة. يمكنك ترك القيمة null في هذه المعلمة إذا كان الترميز غير معروف أو لا يهم. |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | أحيانًا يكون من المستحيل تحميل المورد المطلوب لسبب ما. |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | أحيانًا لأسباب معينة يجب ألا يحدث التحميل عبر كود مخصص. في هذه الحالة يرجى تعيين هذه العلامة إلى True. في هذه الحالة سيحاول المحول استخدام محمل الموارد الافتراضي الداخلي للحصول على تلك النتيجة (كما يحدث عندما لا يتم توفير استراتيجية مخصصة). |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | أحيانًا تكون معرفة نوع MIME للمورد المحمل مفيدة للمحول. يمكنك توفير نوع MIME (إذا كان معروفًا بعد التحميل) في هذه المعلمة. يرجى ترك المعلمة مساوية لـ null عندما يكون نوع MIME غير معروف أو لا يلزم توفيره. |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

ينشئ نسخة من نتيجة التحميل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات |  | يجب دائمًا توفير نتيجة التحميل المخصص، ويمكن أن تكون مصفوفة بطول صفر إذا كان من المستحيل الحصول على أي نتيجة |

### getData {#getData--}
```
public byte[] getData()
```

البيانات الثنائية التي تم تحميلها باستخدام محمل مخصص - يجب تعيينها بعد التحميل

**Returns:**
مصفوفة من قيم البايت

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

أحيانًا يكون ترميز المورد معروفًا بعد أو أثناء التحميل. في هذه الحالة يمكن للكود المخصص أن يزود المحول بهذه المعلومة عبر هذه المعلمة. يمكنك ترك القيمة null في هذه المعلمة إذا كان الترميز غير معروف أو لا يهم.

**Returns:**
مثيل Charset

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

أحيانًا يكون من المستحيل تحميل المورد المطلوب لسبب ما. عدم توفر المورد غالبًا لا يؤدي إلى تعطل التحويلات ويمكن إنشاء مستند النتيجة على أي حال (ولكن ربما بجودة أقل قليلًا، بدون صور إلخ). إذا حدث استثناء أثناء التحميل، فقط امسكه وضعه في هذه المعلمة - أحيانًا تكون هذه المعلومات مفيدة للمحول في عرض النتيجة.

**Returns:**
استثناء

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

أحيانًا تكون معرفة نوع MIME للمورد المحمل مفيدة للمحول. يمكنك توفير نوع MIME (إذا كان معروفًا بعد التحميل) في هذه المعلمة. يرجى ترك المعلمة مساوية لـ null عندما يكون نوع MIME غير معروف أو لا يلزم توفيره.

**Returns:**
قيمة سلسلة

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

أحيانًا لأسباب معينة يجب ألا يحدث التحميل عبر كود مخصص. في هذه الحالة يرجى تعيين هذه العلامة إلى True. في هذه الحالة سيحاول المحول استخدام محمل الموارد الافتراضي الداخلي للحصول على تلك النتيجة (كما يحدث عندما لا يتم توفير استراتيجية مخصصة).

**Returns:**
قيمة منطقية

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
أحيانًا يكون ترميز المورد معروفًا بعد أو أثناء التحميل. في هذه الحالة يمكن للكود المخصص أن يزود المحول بهذه المعلومة عبر هذه المعلمة. يمكنك ترك القيمة null في هذه المعلمة إذا كان الترميز غير معروف أو لا يهم.

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
أحيانًا يكون من المستحيل تحميل المورد المطلوب لسبب ما.

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

أحيانًا لأسباب معينة يجب ألا يحدث التحميل عبر كود مخصص. في هذه الحالة يرجى تعيين هذه العلامة إلى True. في هذه الحالة سيحاول المحول استخدام محمل الموارد الافتراضي الداخلي للحصول على تلك النتيجة (كما يحدث عندما لا يتم توفير استراتيجية مخصصة).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| loadingCancelled |  | قيمة منطقية |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
أحيانًا تكون معرفة نوع MIME للمورد المحمل مفيدة للمحول. يمكنك توفير نوع MIME (إذا كان معروفًا بعد التحميل) في هذه المعلمة. يرجى ترك المعلمة مساوية لـ null عندما يكون نوع MIME غير معروف أو لا يلزم توفيره.
