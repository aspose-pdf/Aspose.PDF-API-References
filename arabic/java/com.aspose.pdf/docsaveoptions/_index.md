---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "خيارات الحفظ للتصدير إلى تنسيق Doc"
type: docs
weight: 1030
url: /ar/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

خيارات الحفظ للتصدير إلى تنسيق Doc

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBatchSize](#getBatchSize--) | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> يمكن استخدام هذا المعالج للتعامل مع أحداث تقدم التحويل، على سبيل المثال يمكن استخدامه لإظهار شريط التقدم أو رسائل حول عدد الصفحات المعالجة حالياً، مثال على شفرة المعالج التي تُظهر التقدم في وحدة التحكم هو : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | احصل على تنسيق الإخراج |
| [getImageResolutionX](#getImageResolutionX--) | دقة الصور المحولة X. |
| [getImageResolutionY](#getImageResolutionY--) | دقة الصور المحولة Y. |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | يُستخدم هذا المعامل لتجميع سطور النص في فقرات. يحدد المسافة بين سطرين نصيين نسبيين. يُحدد بالمئات من نسبة ارتفاع سطر النص. |
| [getMemorySaveModePath](#getMemorySaveModePath--) | يحدد المسار (اسم الملف أو اسم الدليل) لتخزين البيانات المؤقتة عند التحويل في وضع الحفظ في الذاكرة. |
| [getMode](#getMode--) | وضع التعرف. |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | في ملفات PDF قد يتم تمثيل الكلمات داخليًا باستخدام عوامل تُطبع الكلمات بطباعة أحرفها أو مقاطعها بشكل مستقل. لذلك، لاكتشاف الكلمات أحيانًا نحتاج إلى اكتشاف مجموعات من الأحرف المستقلة التي هي في الواقع كلمات. يحدد هذا الإعداد عرض الفراغ بين عناصر النص (الأحرف، المقاطع) الذي يجب معاملته كمسافة بين الكلمات أثناء التعرف على الكلمات في ملف PDF المصدر. (وجود فراغ فارغ على الأقل بهذا العرض بين الأحرف يعني أن عناصر النص تتعلق بكلمات مختلفة). يتم تطبيعه وفق حجم الخط - 1.0 يعني 100٪ من حجم الخط المفترض للكلمة. انتبه! يُستخدم فقط في الحالات التي يحتوي فيها ملف PDF المصدر على خطوط نادرة الاستخدام لا يمكن حساب القيمة المثلى لها من الخط. لذا، في الغالبية العظمى من الحالات لا يغيّر هذا المعامل شيئًا في المستند الناتج. |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | يُستخدم فواصل الفقرات أو الأسطر. |
| [isConvertType3Fonts](#isConvertType3Fonts--) | يحصل أو يضبط التحويل للخطوط Type3. في خطوط Type3، يجب تعريف الحروف عبر تدفقات من عوامل الرسوميات. هذا يعني أنه في مخرجات DOC/DOCX نرى صورًا بدلاً من النص. اضبط هذه العلامة إلى true لتحويل خطوط Type3 إلى TTF والحصول على النص في الملف الناتج. |
| [isRecognizeBullets](#isRecognizeBullets--) | فعّل التعرف على النقاط. |
| [isReSaveFonts](#isReSaveFonts--) | يحصل أو يضبط إجراء إعادة حفظ الخطوط. إذا تم ضبطه على true، نقوم بإعادة تحميل الخطوط في كل صفحة لتجنب تأثير خصائص الخط السابقة وتحميل الخط المُنشأ حديثًا من الصفر. اضبط هذا الخيار على false إذا أردت تحسين الأداء. القيمة الافتراضية هي true; |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | استخدم فواصل الفقرات أو الأسطر |
| [setBatchSize](#setBatchSize-int-) | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | يحصل أو يضبط التحويل للخطوط Type3. في خطوط Type3، يجب تعريف الحروف عبر تدفقات من عوامل الرسوميات. هذا يعني أنه في مخرجات DOC/DOCX نرى صورًا بدلاً من النص. اضبط هذه العلامة إلى true لتحويل خطوط Type3 إلى TTF والحصول على النص في الملف الناتج. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | يمكن استخدام هذا المعالج لمعالجة أحداث تقدم التحويل على سبيل المثال. |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | حدد تنسيق الإخراج |
| [setImageResolutionX](#setImageResolutionX-int-) | دقة الصور المحولة X. |
| [setImageResolutionY](#setImageResolutionY-int-) | دقة الصور المحولة Y. |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | يُستخدم هذا المعامل لتجميع سطور النص في فقرات. يحدد المسافة بين سطرين نصيين نسبيين. يُحدد بالمئات من نسبة ارتفاع سطر النص. |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | يحدد المسار (اسم الملف أو اسم الدليل) لتخزين البيانات المؤقتة عند التحويل في وضع الحفظ في الذاكرة. |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | وضع التعرف. |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | فعّل التعرف على النقاط. |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | في ملفات PDF قد يتم تمثيل الكلمات داخليًا باستخدام عوامل تُطبع الكلمات بطباعة أحرفها أو مقاطعها بشكل مستقل. لذلك، لاكتشاف الكلمات أحيانًا نحتاج إلى اكتشاف مجموعات من الأحرف المستقلة التي هي في الواقع كلمات. يحدد هذا الإعداد عرض الفراغ بين عناصر النص (الأحرف، المقاطع) الذي يجب معاملته كمسافة بين الكلمات أثناء التعرف على الكلمات في ملف PDF المصدر. (وجود فراغ فارغ على الأقل بهذا العرض بين الأحرف يعني أن عناصر النص تتعلق بكلمات مختلفة). يتم تطبيعه وفق حجم الخط - 1.0 يعني 100٪ من حجم الخط المفترض للكلمة. انتبه! يُستخدم فقط في الحالات التي يحتوي فيها ملف PDF المصدر على خطوط نادرة الاستخدام لا يمكن حساب القيمة المثلى لها من الخط. لذا، في الغالبية العظمى من الحالات لا يغيّر هذا المعامل شيئًا في المستند الناتج. |
| [setReSaveFonts](#setReSaveFonts-boolean-) | يحصل أو يضبط إجراء إعادة حفظ الخطوط. إذا تم ضبطه على true، نقوم بإعادة تحميل الخطوط في كل صفحة لتجنب تأثير خصائص الخط السابقة وتحميل الخط المُنشأ حديثًا من الصفر. اضبط هذا الخيار على false إذا أردت تحسين الأداء. القيمة الافتراضية هي true; |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

منشئ

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة.

**Returns:**
قيمة int

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> يمكن استخدام هذا المعالج للتعامل مع أحداث تقدم التحويل، على سبيل المثال يمكن استخدامه لإظهار شريط التقدم أو رسائل حول عدد الصفحات المعالجة حاليًا، مثال على شفرة المعالج التي تُظهر التقدم في وحدة التحكم هو : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
مثيل ConversionProgressEventHandler

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

احصل على تنسيق الإخراج

**Returns:**
عنصر DocFormat @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

دقة الصور المحولة X.

**Returns:**
قيمة int

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

دقة الصور المحولة Y.

**Returns:**
قيمة int

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

يُستخدم هذا المعامل لتجميع سطور النص في فقرات. يحدد المسافة بين سطرين نصيين نسبيين. يُحدد بالمئات من نسبة ارتفاع سطر النص.

**Returns:**
قيمة عائمة

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

يحدد المسار (اسم الملف أو اسم الدليل) لتخزين البيانات المؤقتة عند التحويل في وضع الحفظ في الذاكرة.

**Returns:**
قيمة سلسلة

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

وضع التعرف.

**Returns:**
قيمة RecognitionMode @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

في ملفات PDF قد يتم تمثيل الكلمات داخليًا باستخدام عوامل تُطبع الكلمات بطباعة أحرفها أو مقاطعها بشكل مستقل. لذلك، لاكتشاف الكلمات أحيانًا نحتاج إلى اكتشاف مجموعات من الأحرف المستقلة التي هي في الواقع كلمات. يحدد هذا الإعداد عرض الفراغ بين عناصر النص (الأحرف، المقاطع) الذي يجب معاملته كمسافة بين الكلمات أثناء التعرف على الكلمات في ملف PDF المصدر. (وجود فراغ فارغ على الأقل بهذا العرض بين الأحرف يعني أن عناصر النص تتعلق بكلمات مختلفة). يتم تطبيعه وفق حجم الخط - 1.0 يعني 100٪ من حجم الخط المفترض للكلمة. انتبه! يُستخدم فقط في الحالات التي يحتوي فيها ملف PDF المصدر على خطوط نادرة الاستخدام لا يمكن حساب القيمة المثلى لها من الخط. لذا، في الغالبية العظمى من الحالات لا يغيّر هذا المعامل شيئًا في المستند الناتج.

**Returns:**
القرب النسبي

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

يُستخدم فواصل الفقرات أو الأسطر.

**Returns:**
قيمة منطقية.

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

يحصل أو يضبط التحويل للخطوط Type3. في خطوط Type3، يجب تعريف الحروف عبر تدفقات من عوامل الرسوميات. هذا يعني أنه في مخرجات DOC/DOCX نرى صورًا بدلاً من النص. اضبط هذه العلامة إلى true لتحويل خطوط Type3 إلى TTF والحصول على النص في الملف الناتج.

**Returns:**
قيمة منطقية

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

فعّل التعرف على النقاط.

**Returns:**
قيمة منطقية

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

يحصل أو يضبط إجراء إعادة حفظ الخطوط. إذا تم ضبطه على true، نقوم بإعادة تحميل الخطوط في كل صفحة لتجنب تأثير خصائص الخط السابقة وتحميل الخط المُنشأ حديثًا من الصفر. اضبط هذا الخيار على false إذا أردت تحسين الأداء. القيمة الافتراضية هي true;

**Returns:**
قيمة منطقية

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

استخدم فواصل الفقرات أو الأسطر

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية. |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

يحصل أو يضبط التحويل للخطوط Type3. في خطوط Type3، يجب تعريف الحروف عبر تدفقات من عوامل الرسوميات. هذا يعني أنه في مخرجات DOC/DOCX نرى صورًا بدلاً من النص. اضبط هذه العلامة إلى true لتحويل خطوط Type3 إلى TTF والحصول على النص في الملف الناتج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
يمكن استخدام هذا المعالج لمعالجة أحداث تقدم التحويل على سبيل المثال.

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
حدد تنسيق الإخراج

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

دقة الصور المحولة X.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

دقة الصور المحولة Y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

يُستخدم هذا المعامل لتجميع سطور النص في فقرات. يحدد المسافة بين سطرين نصيين نسبيين. يُحدد بالمئات من نسبة ارتفاع سطر النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
يحدد المسار (اسم الملف أو اسم الدليل) لتخزين البيانات المؤقتة عند التحويل في وضع الحفظ في الذاكرة.

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
وضع التعرف.

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

فعّل التعرف على النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

في ملفات PDF قد يتم تمثيل الكلمات داخليًا باستخدام عوامل تُطبع الكلمات بطباعة أحرفها أو مقاطعها بشكل مستقل. لذلك، لاكتشاف الكلمات أحيانًا نحتاج إلى اكتشاف مجموعات من الأحرف المستقلة التي هي في الواقع كلمات. يحدد هذا الإعداد عرض الفراغ بين عناصر النص (الأحرف، المقاطع) الذي يجب معاملته كمسافة بين الكلمات أثناء التعرف على الكلمات في ملف PDF المصدر. (وجود فراغ فارغ على الأقل بهذا العرض بين الأحرف يعني أن عناصر النص تتعلق بكلمات مختلفة). يتم تطبيعه وفق حجم الخط - 1.0 يعني 100٪ من حجم الخط المفترض للكلمة. انتبه! يُستخدم فقط في الحالات التي يحتوي فيها ملف PDF المصدر على خطوط نادرة الاستخدام لا يمكن حساب القيمة المثلى لها من الخط. لذا، في الغالبية العظمى من الحالات لا يغيّر هذا المعامل شيئًا في المستند الناتج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | القرب النسبي |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

يحصل أو يضبط إجراء إعادة حفظ الخطوط. إذا تم ضبطه على true، نقوم بإعادة تحميل الخطوط في كل صفحة لتجنب تأثير خصائص الخط السابقة وتحميل الخط المُنشأ حديثًا من الصفر. اضبط هذا الخيار على false إذا أردت تحسين الأداء. القيمة الافتراضية هي true;

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
