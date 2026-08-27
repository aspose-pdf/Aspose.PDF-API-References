---
title: "TabStop"
linktitle: "TabStop"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل موضع توقف تبويب مخصص في فقرة."
type: docs
weight: 4840
url: /ar/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

يمثل موضع توقف تبويب مخصص في فقرة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TabStop](#TabStop--) | تهيئ نسخة جديدة من الفئة {@code TabStop}. |
| [TabStop](#TabStop-float-) | تهيئ نسخة جديدة من الفئة {@code TabStop} مع الموضع المحدد. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | يحصل أو يعيّن تعداد {@code AlignmentType} الذي يحدد نوع محاذاة علامة التبويب. |
| [getLeaderType](#getLeaderType--) | يحصل أو يعيّن تعداد {@code TabLeaderType} الذي يحدد نوع القائد للعلامة. |
| [getPosition](#getPosition--) | يحصل أو يعيّن قيمة عائمة تحدد موضع علامة التبويب. |
| [isReadOnly](#isReadOnly--) | يحصل على القيمة التي تشير إلى أن نسخة {@code TabStop} هذه مرفقة بالفعل بـ {@code TextFragment} وأصبحت للقراءة فقط. |
| [setAlignmentType](#setAlignmentType-int-) | يحصل أو يعيّن تعداد {@code AlignmentType} الذي يحدد نوع محاذاة علامة التبويب. |
| [setLeaderType](#setLeaderType-int-) | يحصل أو يعيّن تعداد {@code TabLeaderType} الذي يحدد نوع القائد للعلامة. |
| [setPosition](#setPosition-float-) | يعيّن قيمة عائمة تحدد موضع علامة التبويب. |

### TabStop {#TabStop--}
```
public TabStop()
```

تهيئ نسخة جديدة من الفئة {@code TabStop}.

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

تهيئ نسخة جديدة من الفئة {@code TabStop} مع الموضع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الموضع |  | موضع tab stop. |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

يحصل أو يعيّن تعداد {@code AlignmentType} الذي يحدد نوع محاذاة علامة التبويب.

**Returns:**
عنصر TabAlignmentType @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

يحصل أو يعيّن تعداد {@code TabLeaderType} الذي يحدد نوع القائد للعلامة.

**Returns:**
عنصر TabLeaderType @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

يحصل أو يعيّن قيمة عائمة تحدد موضع علامة التبويب.

**Returns:**
قيمة عائمة

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحصل على القيمة التي تشير إلى أن نسخة {@code TabStop} هذه مرفقة بالفعل بـ {@code TextFragment} وأصبحت للقراءة فقط.

**Returns:**
قيمة منطقية

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

يحصل أو يعيّن تعداد {@code AlignmentType} الذي يحدد نوع محاذاة علامة التبويب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر TabAlignmentType @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

يحصل أو يعيّن تعداد {@code TabLeaderType} الذي يحدد نوع القائد للعلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر TabLeaderType @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

يعيّن قيمة عائمة تحدد موضع علامة التبويب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |
