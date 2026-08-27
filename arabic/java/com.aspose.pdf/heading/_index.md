---
title: "العنوان"
linktitle: "العنوان"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل العنوان."
type: docs
weight: 1890
url: /ar/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

يمثل العنوان.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Heading](#Heading--) | للاستخدام الداخلي فقط |
| [Heading](#Heading-int-) | يُهيئ نسخة جديدة من الفئة Cell. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | استنساخ العنوان مع جميع المقاطع. |
| [deepClone](#deepClone--) | استنساخ العنوان. |
| [getDestinationPage](#getDestinationPage--) | يحصل على الصفحة الوجهة. |
| [getLevel](#getLevel--) | يحصل على المستوى. |
| [getStartNumber](#getStartNumber--) | يحصل على رقم بدء العنوان. |
| [getStyle](#getStyle--) | يحصل أو يضبط النمط. |
| [getTocPage](#getTocPage--) | يحصل على الصفحة التي تحتوي على هذا العنوان. |
| [getTop](#getTop--) | يحصل على إحداثي Y العلوي لهذا العنوان (للاستخدام الداخلي). |
| [getUserLabel](#getUserLabel--) | يحصل أو يضبط تسمية المستخدم. |
| [isAutoSequence](#isAutoSequence--) | يحصل على ما إذا كان يجب ترقيم العنوان تلقائيًا. |
| [isInList](#isInList--) | يحصل على ما إذا كان العنوان يجب أن يكون في قائمة الفهرس. |
| [setAutoSequence](#setAutoSequence-boolean-) | يضبط ما إذا كان يجب ترقيم العنوان تلقائيًا. |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | يضبط الصفحة الوجهة. |
| [setInList](#setInList-boolean-) | يضبط ما إذا كان العنوان يجب أن يكون في قائمة الفهرس. |
| [setLevel](#setLevel-int-) | يضبط المستوى. |
| [setStartNumber](#setStartNumber-int-) | يحصل على رقم بداية العنوان. القيمة: startNumber. |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | يضبط أو يضبط النمط. |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | يضبط الصفحة التي تحتوي على هذا العنوان. |
| [setTop](#setTop-double-) | يضبط القيمة العليا Y لهذه العناوين (للاستخدام الداخلي). |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | يحصل أو يضبط تسمية المستخدم. |

### Heading {#Heading--}
```
public Heading()
```

للاستخدام الداخلي فقط

### Heading {#Heading-int-}
```
public Heading(int level)
```

يُهيئ نسخة جديدة من الفئة Cell.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المستوى |  | مستوى العناوين. |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

استنساخ العنوان مع جميع المقاطع.

**Returns:**
الكائن المستنسخ

### deepClone {#deepClone--}
```
public Object deepClone()
```

استنساخ العنوان.

**Returns:**
الكائن المستنسخ

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

يحصل على الصفحة الوجهة.

**Returns:**
صفحة الوجهة.

### getLevel {#getLevel--}
```
public int getLevel()
```

يحصل على المستوى.

**Returns:**
مستوى العنوان.

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

يحصل على رقم بدء العنوان.

**Returns:**
القيمة: startNumber.

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

يحصل أو يضبط النمط.

**Returns:**
نمط العنوان.

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

يحصل على الصفحة التي تحتوي على هذا العنوان.

**Returns:**
الصفحة.

### getTop {#getTop--}
```
public double getTop()
```

يحصل على إحداثي Y العلوي لهذا العنوان (للاستخدام الداخلي).

**Returns:**
القيمة العليا Y

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

يحصل أو يضبط تسمية المستخدم.

**Returns:**
كائن TextSegment

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

يحصل على ما إذا كان يجب ترقيم العنوان تلقائيًا.

**Returns:**
ال IsAutoSequens.

### isInList {#isInList--}
```
public boolean isInList()
```

يحصل على ما إذا كان العنوان يجب أن يكون في قائمة الفهرس.

**Returns:**
ال IsInList.

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

يضبط ما إذا كان يجب ترقيم العنوان تلقائيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | ال IsAutoSequens. |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
يضبط الصفحة الوجهة.

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

يضبط ما إذا كان العنوان يجب أن يكون في قائمة الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | ال IsInList. |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

يضبط المستوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مستوى العنوان. |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

يحصل على رقم بداية العنوان. القيمة: startNumber.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | ال startNumber. |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
يضبط أو يضبط النمط.

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
يضبط الصفحة التي تحتوي على هذا العنوان.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

يضبط القيمة العليا Y لهذه العناوين (للاستخدام الداخلي).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | القيمة العليا Y |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
يحصل أو يضبط تسمية المستخدم.
