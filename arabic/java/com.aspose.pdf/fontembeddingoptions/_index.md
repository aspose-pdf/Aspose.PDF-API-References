---
title: "FontEmbeddingOptions"
linktitle: "FontEmbeddingOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "معيار PDF/A يتطلب أن يتم تضمين جميع الخطوط في المستند. تحتوي هذه الفئة على علامات لحالات عدم إمكانية تضمين بعض الخطوط لأن هذا الخط غير موجود."
type: docs
weight: 1680
url: /ar/java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontEmbeddingOptions

```
public class FontEmbeddingOptions extends Object
```

يتطلب معيار PDF/A أن يتم تضمين جميع الخطوط في المستند. تتضمن هذه الفئة علامات للحالات التي لا يمكن فيها تضمين بعض الخطوط لأن هذا الخط غير موجود على جهاز الكمبيوتر الوجهة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FontEmbeddingOptions](#FontEmbeddingOptions--) | ينشئ مثيلًا جديدًا من الفئة {@link FontEmbeddingOptions}. يحدد هذا المُنشئ القيمة الافتراضية للخاصية {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) إلى {@code }. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getUseDefaultSubstitution](#getUseDefaultSubstitution--) | يشير إلى ما إذا كان سيتم استبدال الخط غير المضمن باستخدام استراتيجية استبدال الخط الافتراضية. القيمة الافتراضية هي false؛ |
| [setUseDefaultSubstitution](#setUseDefaultSubstitution-boolean-) | يشير إلى ما إذا كان سيتم استبدال الخط غير المضمن باستخدام استراتيجية استبدال الخط الافتراضية. القيمة الافتراضية هي false؛ |

### FontEmbeddingOptions {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```

ينشئ مثيلًا جديدًا من الفئة {@link FontEmbeddingOptions}. يحدد هذا المُنشئ القيمة الافتراضية للخاصية {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) إلى {@code }.

### getUseDefaultSubstitution {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```

يشير إلى ما إذا كان سيتم استبدال الخط غير المضمن باستخدام استراتيجية استبدال الخط الافتراضية. القيمة الافتراضية هي false؛

**Returns:**
قيمة منطقية

### setUseDefaultSubstitution {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```

يشير إلى ما إذا كان سيتم استبدال الخط غير المضمن باستخدام استراتيجية استبدال الخط الافتراضية. القيمة الافتراضية هي false؛

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
