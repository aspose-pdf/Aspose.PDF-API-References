---
title: "شرطة"
linktitle: "شرطة"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل نمط الخط المتقطع."
type: docs
weight: 910
url: /ar/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

فئة تمثل نمط الخط المتقطع.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Dash](#Dash-int:A-) | منشئ لـ Dash. يحدد نمطًا من الشرطات والفجوات التي ستُستخدم في رسم حد منقط. |
| [Dash](#Dash-int-int-) | منشئ لـ Dash. يحدد حدًا منقطًا باستخدام الشرط والفجوة المحددين، واللذان يظلان ثابتين لكامل الحد المنقط. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getOff](#getOff--) | يحصل أو يضبط طول الفجوة الأولى بين الشرطات. |
| [getOn](#getOn--) | يحصل أو يضبط طول الشرط الأول. |
| [getPattern](#getPattern--) | يحصل على مصفوفة الشرطات التي تحدد نمطًا من الشرطات والفجوات التي ستُستخدم في رسم حد منقط. |
| [setOff](#setOff-int-) | يحصل أو يضبط طول الفجوة الأولى بين الشرطات. |
| [setOn](#setOn-int-) | يحصل أو يضبط طول الشرط الأول. |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

منشئ لـ Dash. يحدد نمطًا من الشرطات والفجوات التي ستُستخدم في رسم حد منقط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نمط |  | مصفوفة شرطات (بحد أدنى قيمتين) تحدد نمطًا من الشرطات والفجوات التي ستُستخدم في رسم حد منقط. |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

منشئ لـ Dash. يحدد حدًا منقطًا باستخدام الشرط والفجوة المحددين، واللذان يظلان ثابتين لكامل الحد المنقط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تشغيل |  | طول الشرط. |
| إيقاف |  | طول الفجوة. |

### getOff {#getOff--}
```
public final int getOff()
```

يحصل أو يضبط طول الفجوة الأولى بين الشرطات.

**Returns:**
قيمة int

### getOn {#getOn--}
```
public final int getOn()
```

يحصل أو يضبط طول الشرط الأول.

**Returns:**
قيمة int

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

يحصل على مصفوفة الشرطات التي تحدد نمطًا من الشرطات والفجوات التي ستُستخدم في رسم حد منقط.

**Returns:**
مصفوفة int

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

يحصل أو يضبط طول الفجوة الأولى بين الشرطات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

يحصل أو يضبط طول الشرط الأول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
