---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحتوي على خيارات تحميل/استيراد ملف EPUB إلى مستند PDF."
type: docs
weight: 1220
url: /ar/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

يحتوي على خيارات تحميل/استيراد ملف EPUB إلى مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | ينشئ خيارات التحميل الافتراضية لتحويل ملف EPUB إلى مستند PDF. حجم صفحة PDF الافتراضي - A4 300dpi 2480 × 3508. |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | ينشئ خيارات التحميل الافتراضية لتحويل ملف EPUB إلى مستند PDF. حجم صفحة PDF الافتراضي - A4 300dpi 2480 × 3508. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCustomCss](#getCustomCss--) | يحصل أو يعيّن الـ Css المخصص لتطبيقه عند فتح مستند Epub. |
| [getEngineType](#getEngineType--) | اختر نوع المحرك للتحويل من EPUB إلى PDF. القيمة الافتراضية هي EngineType.NEW |
| [getMargin](#getMargin--) | يحصل على مرجع إلى الكائن الذي يمثل معلومات الهوامش. |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | يمثّل وضعية استخدام مساحة الهوامش - يحدد معالجة التعليمات (إن وجدت) للـ CSS في المستند المستورد المتعلقة باستخدام الهوامش. |
| [getPageSize](#getPageSize--) | يحصل على حجم الصفحة الناتجة للاستيراد. |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | تنبيه! تم تنفيذ الميزة ولكن لم تُضف بعد إلى واجهة برمجة التطبيقات العامة بسبب وجود مشكلة عائق في طبقة OSHARED تم الكشف عنها في المستند النموذجي. تمثّل وضعية استخدام حجم الصفحة أثناء التحويل. الصيغ (مثل HTML، EPUB إلخ) عادةً ما تكون ذات تصميم عائم، لذا تسمح بتناسب حجم الصفحة المطلوب. لكن أحيانًا يحتوي المحتوى على مواضع أفقية أو حجم محدد لا يسمح بوضع المحتوى داخل حجم الصفحة المطلوب. في هذه الحالة يمكننا تحديد ما يجب القيام به (أي عندما لا يتناسب حجم المحتوى مع حجم الصفحة الأولي المطلوب لوثيقة PDF الناتجة). |
| [setCustomCss](#setCustomCss-java.lang.String-) | يحصل أو يعيّن الـ Css المخصص لتطبيقه عند فتح مستند Epub. |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | اختر نوع المحرك للتحويل من EPUB إلى PDF. القيمة الافتراضية هي EngineType.NEW |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | يحصل على مرجع إلى الكائن الذي يمثل معلومات الهوامش. |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | يمثّل وضعية استخدام مساحة الهوامش - يحدد معالجة التعليمات (إن وجدت) للـ CSS في المستند المستورد المتعلقة باستخدام الهوامش. |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | تنبيه! تم تنفيذ الميزة ولكن لم تُضف بعد إلى واجهة برمجة التطبيقات العامة بسبب وجود مشكلة عائق في طبقة OSHARED تم الكشف عنها في المستند النموذجي. تمثّل وضعية استخدام حجم الصفحة أثناء التحويل. الصيغ (مثل HTML، EPUB إلخ) عادةً ما تكون ذات تصميم عائم، لذا تسمح بتناسب حجم الصفحة المطلوب. لكن أحيانًا يحتوي المحتوى على مواضع أفقية أو حجم محدد لا يسمح بوضع المحتوى داخل حجم الصفحة المطلوب. في هذه الحالة يمكننا تحديد ما يجب القيام به (أي عندما لا يتناسب حجم المحتوى مع حجم الصفحة الأولي المطلوب لوثيقة PDF الناتجة). |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

ينشئ خيارات التحميل الافتراضية لتحويل ملف EPUB إلى مستند PDF. حجم صفحة PDF الافتراضي - A4 300dpi 2480 × 3508.

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
ينشئ خيارات التحميل الافتراضية لتحويل ملف EPUB إلى مستند PDF. حجم صفحة PDF الافتراضي - A4 300dpi 2480 × 3508.

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

يحصل أو يعيّن الـ Css المخصص لتطبيقه عند فتح مستند Epub.

**Returns:**
قيمة سلسلة

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

اختر نوع المحرك للتحويل من EPUB إلى PDF. القيمة الافتراضية هي EngineType.NEW

**Returns:**
عنصر EngineType

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

يحصل على مرجع إلى الكائن الذي يمثل معلومات الهوامش.

**Returns:**
كائن MarginInfo

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

يمثّل وضعية استخدام مساحة الهوامش - يحدد معالجة التعليمات (إن وجدت) للـ CSS في المستند المستورد المتعلقة باستخدام الهوامش.

**Returns:**
قيمة MarginsAreaUsageModes @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

يحصل على حجم الصفحة الناتجة للاستيراد.

**Returns:**
كائن Dimension2D

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

تنبيه! تم تنفيذ الميزة ولكن لم تُضف بعد إلى واجهة برمجة التطبيقات العامة بسبب وجود مشكلة عائق في طبقة OSHARED تم الكشف عنها في المستند النموذجي. تمثّل وضعية استخدام حجم الصفحة أثناء التحويل. الصيغ (مثل HTML، EPUB إلخ) عادةً ما تكون ذات تصميم عائم، لذا تسمح بتناسب حجم الصفحة المطلوب. لكن أحيانًا يحتوي المحتوى على مواضع أفقية أو حجم محدد لا يسمح بوضع المحتوى داخل حجم الصفحة المطلوب. في هذه الحالة يمكننا تحديد ما يجب القيام به (أي عندما لا يتناسب حجم المحتوى مع حجم الصفحة الأولي المطلوب لوثيقة PDF الناتجة).

**Returns:**
قيمة PageSizeAdjustmentModes @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
يحصل أو يعيّن الـ Css المخصص لتطبيقه عند فتح مستند Epub.

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
اختر نوع المحرك للتحويل من EPUB إلى PDF. القيمة الافتراضية هي EngineType.NEW

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
يحصل على مرجع إلى الكائن الذي يمثل معلومات الهوامش.

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

يمثّل وضعية استخدام مساحة الهوامش - يحدد معالجة التعليمات (إن وجدت) للـ CSS في المستند المستورد المتعلقة باستخدام الهوامش.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| marginsAreaUsageMode |  | قيمة MarginsAreaUsageModes @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

تنبيه! تم تنفيذ الميزة ولكن لم تُضف بعد إلى واجهة برمجة التطبيقات العامة بسبب وجود مشكلة عائق في طبقة OSHARED تم الكشف عنها في المستند النموذجي. تمثّل وضعية استخدام حجم الصفحة أثناء التحويل. الصيغ (مثل HTML، EPUB إلخ) عادةً ما تكون ذات تصميم عائم، لذا تسمح بتناسب حجم الصفحة المطلوب. لكن أحيانًا يحتوي المحتوى على مواضع أفقية أو حجم محدد لا يسمح بوضع المحتوى داخل حجم الصفحة المطلوب. في هذه الحالة يمكننا تحديد ما يجب القيام به (أي عندما لا يتناسب حجم المحتوى مع حجم الصفحة الأولي المطلوب لوثيقة PDF الناتجة).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | قيمة PageSizeAdjustmentModes @see PageSizeAdjustmentModes |
