---
title: "PrintPaperSize"
linktitle: "PrintPaperSize"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد حجم قطعة الورق."
type: docs
weight: 100
url: /ar/java/com.aspose.pdf.printing/printpapersize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPaperSize

```
public class PrintPaperSize extends Object
```

يحدد حجم قطعة الورق.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PrintPaperSize](#PrintPaperSize--) | ينشئ مثيلاً جديداً لفئة PaperSize. |
| [PrintPaperSize](#PrintPaperSize-int-java.lang.String-int-int-) | ينشئ مثيلاً جديداً لفئة PaperSize. |
| [PrintPaperSize](#PrintPaperSize-java.lang.String-int-int-) | ينشئ مثيلاً جديداً لفئة PaperSize. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHeight](#getHeight--) | يحصل على ارتفاع الورق أو يضبطه، بالجزء المئوي من البوصة. |
| [getKind](#getKind--) | يحصل على نوع الورق. |
| [getPaperName](#getPaperName--) | يحصل أو يضبط اسم نوع الورق. |
| [getRawKind](#getRawKind--) | يحصل أو يضبط عددًا صحيحًا يمثل أحد قيم PaperSize أو قيمة مخصصة. |
| [getWidth](#getWidth--) | يحصل أو يضبط عرض الورق، بوحدات مئوية من البوصة. |
| [setHeight](#setHeight-int-) | يحصل على ارتفاع الورق أو يضبطه، بالجزء المئوي من البوصة. |
| [setPaperName](#setPaperName-java.lang.String-) | يحصل على اسم نوع الورق. |
| [setWidth](#setWidth-int-) | يضبط عرض الورق، بوحدات مئوية من البوصة. |
| [toNativePaperSize](#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-) | يحوّل {@link PaperSize} إلى System.Drawing.Printing.PaperSize الخاص بنظام Windows. |
| [toString](#toString--) | يحصل على اسم هذه الحالة. |

### PrintPaperSize {#PrintPaperSize--}
```
public PrintPaperSize()
```

ينشئ مثيلاً جديداً لفئة PaperSize.

### PrintPaperSize {#PrintPaperSize-int-java.lang.String-int-int-}
ينشئ مثيلاً جديداً لفئة PaperSize.

### PrintPaperSize {#PrintPaperSize-java.lang.String-int-int-}
ينشئ مثيلاً جديداً لفئة PaperSize.

### getHeight {#getHeight--}
```
public int getHeight()
```

يحصل على ارتفاع الورق أو يضبطه، بالجزء المئوي من البوصة.

**Returns:**
قيمة int

### getKind {#getKind--}
```
public int getKind()
```

يحصل على نوع الورق.

**Returns:**
قيمة int @see PrinterPaperKind

### getPaperName {#getPaperName--}
```
public String getPaperName()
```

يحصل أو يضبط اسم نوع الورق.

**Returns:**
قيمة سلسلة

### getRawKind {#getRawKind--}
```
public int getRawKind()
```

يحصل أو يضبط عددًا صحيحًا يمثل أحد قيم PaperSize أو قيمة مخصصة.

**Returns:**
قيمة int

### getWidth {#getWidth--}
```
public int getWidth()
```

يحصل أو يضبط عرض الورق، بوحدات مئوية من البوصة.

**Returns:**
قيمة int

### setHeight {#setHeight-int-}
```
public void setHeight(int value)
```

يحصل على ارتفاع الورق أو يضبطه، بالجزء المئوي من البوصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPaperName {#setPaperName-java.lang.String-}
يحصل على اسم نوع الورق.

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

يضبط عرض الورق، بوحدات مئوية من البوصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### toNativePaperSize {#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-}
يحوّل {@link PaperSize} إلى System.Drawing.Printing.PaperSize الخاص بنظام Windows.

### toString {#toString--}
```
public String toString()
```

يحصل على اسم هذه الحالة.

**Returns:**
قيمة سلسلة
