---
title: "TextProperties"
linktitle: "TextProperties"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خصائص النص مثل: حجم النص، اللون، النمط، إلخ."
type: docs
weight: 740
url: /ar/java/com.aspose.pdf.facades/textproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.TextProperties

```
public final class TextProperties extends Object
```

يمثل خصائص النص مثل: حجم النص، اللون، النمط، إلخ.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextProperties](#TextProperties-double-) | ينشئ كائن {@code TextProperties} للحجم النص المحدد |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColor](#getColor--) | يحصل على لون النص. |
| [getTextSize](#getTextSize--) | يحصل على حجم النص. |
| [isColorSpecified](#isColorSpecified--) | يحصل على قيمة تشير إلى ما إذا كانت خاصية {@code Color} محددة. |
| [isTextSizeSpecified](#isTextSizeSpecified--) | يحصل على قيمة تشير إلى ما إذا كانت خاصية {@code TextSize} محددة. |
| [setColor](#setColor-java.awt.Color-) | يضبط لون النص. |
| [setTextSize](#setTextSize-double-) | يضبط حجم النص. |

### TextProperties {#TextProperties-double-}
```
public TextProperties(double textSize)
```

ينشئ كائن {@code TextProperties} للحجم النص المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| textSize |  | قيمة حجم النص. |

### getColor {#getColor--}
```
public Color getColor()
```

يحصل على لون النص.

**Returns:**
كائن Color

### getTextSize {#getTextSize--}
```
public double getTextSize()
```

يحصل على حجم النص.

**Returns:**
قيمة double

### isColorSpecified {#isColorSpecified--}
```
public boolean isColorSpecified()
```

يحصل على قيمة تشير إلى ما إذا كانت خاصية {@code Color} محددة.

**Returns:**
قيمة منطقية

### isTextSizeSpecified {#isTextSizeSpecified--}
```
public boolean isTextSizeSpecified()
```

يحصل على قيمة تشير إلى ما إذا كانت خاصية {@code TextSize} محددة.

**Returns:**
قيمة منطقية

### setColor {#setColor-java.awt.Color-}
يضبط لون النص.

### setTextSize {#setTextSize-double-}
```
public void setTextSize(double value)
```

يضبط حجم النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |
