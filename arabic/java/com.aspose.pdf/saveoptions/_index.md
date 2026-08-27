---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "نوع SaveOptions يحتفظ بمستوى التجريد على خيارات الحفظ الفردية"
type: docs
weight: 4370
url: /ar/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

نوع SaveOptions يحتفظ بمستوى التجريد على خيارات الحفظ الفردية

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | تنسيق حفظ البيانات. |
| [getWarningHandler](#getWarningHandler--) | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction الذي يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |
| [isCacheGlyphs](#isCacheGlyphs--) | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل pdf إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [isCloseResponse](#isCloseResponse--) | يحصل على قيمة منطقية تشير إلى ما إذا كان كائن Response سيُغلق بعد حفظ المستند في الاستجابة. |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل pdf إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [setCloseResponse](#setCloseResponse-boolean-) | يعيّن قيمة منطقية تشير إلى ما إذا كان كائن Response سيُغلق بعد حفظ المستند في الاستجابة. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction الذي يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

تنسيق حفظ البيانات.

**Returns:**
قيمة SaveFormat @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction الذي يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ.

**Returns:**
قيمة IWarningCallback

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل pdf إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة.

**Returns:**
قيمة منطقية

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

يحصل على قيمة منطقية تشير إلى ما إذا كان كائن Response سيُغلق بعد حفظ المستند في الاستجابة.

**Returns:**
قيمة منطقية

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل pdf إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

يعيّن قيمة منطقية تشير إلى ما إذا كان كائن Response سيُغلق بعد حفظ المستند في الاستجابة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction الذي يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ.
