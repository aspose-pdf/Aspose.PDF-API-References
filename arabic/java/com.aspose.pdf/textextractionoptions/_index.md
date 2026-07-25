---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات استخراج النص"
type: docs
weight: 5060
url: /ar/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

يمثل خيارات استخراج النص

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | يُهيئ مثيلًا جديدًا لكائن {@code TextExtractionOptions} للوضع المحدد لتنسيق النص. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | يحصل على وضع التنسيق. |
| [getScaleFactor](#getScaleFactor--) | يحصل على العامل الذي سيُطبق لتكبير حجم الخط أثناء الاستخراج في الوضع النقي. ضبط قيمة أقل يؤدي إلى مزيد من الفراغات في النص المستخرج. القيمة الافتراضية هي 1 - بدون تكبير؛ ضبط القيمة إلى صفر يسمح للخوارزمية باختيار التكبير تلقائيًا. |
| [setFormattingMode](#setFormattingMode-int-) | يضبط وضع التنسيق. |
| [setScaleFactor](#setScaleFactor-double-) | يضبط العامل الذي سيُطبق لتكبير حجم الخط أثناء الاستخراج في الوضع النقي. ضبط قيمة أقل يؤدي إلى مزيد من الفراغات في النص المستخرج (من 1 إلى 10). القيمة الافتراضية هي 1 - بدون تكبير؛ ضبط القيمة إلى صفر يسمح للخوارزمية باختيار التكبير تلقائيًا. |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

يُهيئ مثيلًا جديدًا لكائن {@code TextExtractionOptions} للوضع المحدد لتنسيق النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| formattingMode |  | قيمة وضع تنسيق النص. @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

يحصل على وضع التنسيق.

**Returns:**
قيمة TextFormattingMode @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

يحصل على العامل الذي سيُطبق لتكبير حجم الخط أثناء الاستخراج في الوضع النقي. ضبط قيمة أقل يؤدي إلى مزيد من الفراغات في النص المستخرج. القيمة الافتراضية هي 1 - بدون تكبير؛ ضبط القيمة إلى صفر يسمح للخوارزمية باختيار التكبير تلقائيًا.

**Returns:**
قيمة double

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

يضبط وضع التنسيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة TextFormattingMode @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

يضبط العامل الذي سيُطبق لتكبير حجم الخط أثناء الاستخراج في الوضع النقي. ضبط قيمة أقل يؤدي إلى مزيد من الفراغات في النص المستخرج (من 1 إلى 10). القيمة الافتراضية هي 1 - بدون تكبير؛ ضبط القيمة إلى صفر يسمح للخوارزمية باختيار التكبير تلقائيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |
