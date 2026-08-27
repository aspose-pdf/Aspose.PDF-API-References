---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد الإعدادات التي تنطبق على صفحة مطبوعة واحدة."
type: docs
weight: 90
url: /ar/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

يحدد الإعدادات التي تنطبق على صفحة مطبوعة واحدة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | يُنشئ مثلاً جديداً من الفئة PageSettings باستخدام الطابعة الافتراضية. |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | يُنشئ مثلاً جديداً من الفئة PageSettings باستخدام الطابعة الافتراضية. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds](#getBounds--) | يحصل على حجم الصفحة، مع مراعاة اتجاه الصفحة المحدد بواسطة خاصية Landscape. |
| [getHardMarginX](#getHardMarginX--) | يحصل على الإحداثي السيني، بوحدات المئوية من البوصة، للهوامش الصلبة على يسار الصفحة. |
| [getHardMarginY](#getHardMarginY--) | يحصل على الإحداثي الصادي، بوحدات المئوية من البوصة، للهوامش الصلبة في أعلى الصفحة. |
| [getMargins](#getMargins--) | يحصل على الهوامش لهذه الصفحة. |
| [getPageSettings](#getPageSettings--) | يحصل على إعدادات الصفحة |
| [getPaperSize](#getPaperSize--) | يحصل على حجم الورق للصفحة. |
| [getPaperSource](#getPaperSource--) | يحصل على مصدر ورق الصفحة؛ على سبيل المثال، صينية الطابعة العلوية. |
| [getPrintableArea](#getPrintableArea--) | يحصل على حدود المنطقة القابلة للطباعة للصفحة بالنسبة للطابعة. |
| [getPrinterResolution](#getPrinterResolution--) | يحصل على دقة الطابعة للصفحة. |
| [getPrinterSettings](#getPrinterSettings--) | يحصل على إعدادات الطابعة المرتبطة بالصفحة. |
| [isColor](#isColor--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب طباعة الصفحة بالألوان. |
| [isLandscape](#isLandscape--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصفحة مطبوعة في وضعية أفقية أو عمودية. |
| [setColor](#setColor-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب طباعة الصفحة بالألوان. |
| [setLandscape](#setLandscape-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصفحة مطبوعة في وضعية أفقية أو عمودية. |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | يضبط الهوامش لهذه الصفحة. |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | يضبط حجم الورق للصفحة. |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | يضبط مصدر ورق الصفحة؛ على سبيل المثال، صينية الطابعة العلوية. |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | يضبط دقة الطابعة للصفحة. |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | يضبط إعدادات الطابعة المرتبطة بالصفحة. |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

يُنشئ مثلاً جديداً من الفئة PageSettings باستخدام الطابعة الافتراضية.

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
يُنشئ مثلاً جديداً من الفئة PageSettings باستخدام الطابعة الافتراضية.

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

يحصل على حجم الصفحة، مع مراعاة اتجاه الصفحة المحدد بواسطة خاصية Landscape.

**Returns:**
كائن Rectangle

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

يحصل على الإحداثي السيني، بوحدات المئوية من البوصة، للهوامش الصلبة على يسار الصفحة.

**Returns:**
قيمة عائمة

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

يحصل على الإحداثي الصادي، بوحدات المئوية من البوصة، للهوامش الصلبة في أعلى الصفحة.

**Returns:**
قيمة عائمة

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

يحصل على الهوامش لهذه الصفحة.

**Returns:**
كائن PrinterMargins

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

يحصل على إعدادات الصفحة

**Returns:**
كائن PageSettings

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

يحصل على حجم الورق للصفحة.

**Returns:**
كائن PrintPaperSize

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

يحصل على مصدر ورق الصفحة؛ على سبيل المثال، صينية الطابعة العلوية.

**Returns:**
كائن PrintPaperSource

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

يحصل على حدود المنطقة القابلة للطباعة للصفحة بالنسبة للطابعة.

**Returns:**
كائن Rectangle

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

يحصل على دقة الطابعة للصفحة.

**Returns:**
كائن PdfPrinterResolution

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

يحصل على إعدادات الطابعة المرتبطة بالصفحة.

**Returns:**
كائن PdfPrinterSettings

### isColor {#isColor--}
```
public boolean isColor()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب طباعة الصفحة بالألوان.

**Returns:**
قيمة منطقية

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصفحة مطبوعة في وضعية أفقية أو عمودية.

**Returns:**
قيمة منطقية

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب طباعة الصفحة بالألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصفحة مطبوعة في وضعية أفقية أو عمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
يضبط الهوامش لهذه الصفحة.

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
يضبط حجم الورق للصفحة.

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
يضبط مصدر ورق الصفحة؛ على سبيل المثال، صينية الطابعة العلوية.

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
يضبط دقة الطابعة للصفحة.

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
يضبط إعدادات الطابعة المرتبطة بالصفحة.
