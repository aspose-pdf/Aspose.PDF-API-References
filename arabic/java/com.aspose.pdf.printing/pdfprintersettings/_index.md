---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد معلومات حول كيفية طباعة المستند، بما في ذلك الطابعة التي تقوم بطباعته."
type: docs
weight: 50
url: /ar/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

يحدد معلومات حول كيفية طباعة المستند، بما في ذلك الطابعة التي تقوم بطباعته.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | يُنشئ مثيلاً جديداً لفئة PrinterSettings. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [canDuplex](#canDuplex--) | يحصل على قيمة تشير إلى ما إذا كانت الطابعة تدعم الطباعة على الوجهين. |
| [createMeasurementGraphics](#createMeasurementGraphics--) | احصل على كائن Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | احصل على كائن Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | احصل على كائن Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | احصل على كائن Graphics2D |
| [deepClone](#deepClone--) | احصل على كائن مستنسخ |
| [getCopies](#getCopies--) | يحصل على عدد النسخ من المستند للطباعة. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | يحصل على إعدادات الصفحة الافتراضية لهذه الطابعة. |
| [getDuplex](#getDuplex--) | يحصل على أو يضبط إعداد الطابعة للطباعة على الوجهين. |
| [getFromPage](#getFromPage--) | يحصل على أو يضبط رقم الصفحة الأولى للطباعة. |
| [getInstalledPrinters](#getInstalledPrinters--) | يحصل على أسماء جميع الطابعات المثبتة على الحاسوب. |
| [getLandscapeAngle](#getLandscapeAngle--) | يحصل على الزاوية، بالدرجات، التي يتم فيها تدوير الوضع العمودي لإنتاج الوضع الأفقي. |
| [getMaximumCopies](#getMaximumCopies--) | يحصل على الحد الأقصى لعدد النسخ التي تسمح الطابعة للمستخدم بطباعتها في آن واحد. |
| [getMaximumPage](#getMaximumPage--) | يحصل على أو يضبط الحد الأقصى للصفحة FromPage أو ToPage التي يمكن اختيارها في مربع حوار الطباعة. |
| [getMinimumPage](#getMinimumPage--) | يحصل على أو يضبط الحد الأدنى للصفحة FromPage أو ToPage التي يمكن اختيارها في مربع حوار الطباعة. |
| [getPaperSizes](#getPaperSizes--) | يحصل على أحجام الورق التي تدعمها هذه الطابعة. |
| [getPaperSources](#getPaperSources--) | يحصل على صواني مصدر الورق المتاحة في الطابعة. |
| [getPrinterName](#getPrinterName--) | يحصل على أو يضبط اسم الطابعة المستخدمة. |
| [getPrinterResolutions](#getPrinterResolutions--) | يحصل على جميع الدقات التي تدعمها هذه الطابعة. |
| [getPrinterSettings](#getPrinterSettings--) | إرجاع كائن PrinterSettings |
| [getPrintFileName](#getPrintFileName--) | يحصل على أو يضبط اسم الملف عند الطباعة إلى ملف. |
| [getPrintRange](#getPrintRange--) | يحصل على أو يضبط أرقام الصفحات التي حددها المستخدم للطباعة. |
| [getSelectedPages](#getSelectedPages--) | يحصل على عدد الصفحات المحددة للطباعة. |
| [getToPage](#getToPage--) | يحصل على أو يضبط رقم الصفحة الأخيرة للطباعة. |
| [isCollate](#isCollate--) | يحصل على أو يضبط قيمة تشير إلى ما إذا كان المستند المطبوع مرتبًا. |
| [isDefaultPrinter](#isDefaultPrinter--) | يحصل على قيمة تشير إلى ما إذا كانت خاصية PrinterName تعين الطابعة الافتراضية، باستثناء عندما يقوم المستخدم بتعيين PrinterName صراحةً. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | يحصل على قيمة تشير إلى ما إذا كانت الطابعة تدعم DirectPrinting |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | يحصل على قيمة تشير إلى ما إذا كانت الطابعة تدعم DirectPrinting |
| [isPlotter](#isPlotter--) | يحصل على قيمة تشير إلى ما إذا كانت الطابعة جهاز رسم. |
| [isPrintToFile](#isPrintToFile--) | يحصل على قيمة تشير إلى ما إذا كان ناتج الطباعة يُرسل إلى ملف بدلاً من منفذ. |
| [isSupportsColor](#isSupportsColor--) | يحصل على قيمة تشير إلى ما إذا كانت هذه الطابعة تدعم الطباعة بالألوان. |
| [isValid](#isValid--) | يحصل على قيمة تشير إلى ما إذا كانت خاصية PrinterName تعين طابعة صالحة. |
| [setCollate](#setCollate-boolean-) | يحصل على أو يضبط قيمة تشير إلى ما إذا كان المستند المطبوع مرتبًا. |
| [setCopies](#setCopies-short-) | يضبط عدد نسخ المستند للطباعة. |
| [setDuplex](#setDuplex-int-) | يحصل على أو يضبط إعداد الطابعة للطباعة على الوجهين. |
| [setFromPage](#setFromPage-int-) | يحصل على أو يضبط رقم الصفحة الأولى للطباعة. |
| [setMaximumPage](#setMaximumPage-int-) | يحصل على أو يضبط الحد الأقصى للصفحة FromPage أو ToPage التي يمكن اختيارها في مربع حوار الطباعة. |
| [setMinimumPage](#setMinimumPage-int-) | يحصل على أو يضبط الحد الأدنى للصفحة FromPage أو ToPage التي يمكن اختيارها في مربع حوار الطباعة. |
| [setPrinterName](#setPrinterName-java.lang.String-) | يضبط اسم الطابعة المستخدمة. |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | يضبط اسم الملف للطباعة. |
| [setPrintRange](#setPrintRange-int-) | يضبط أرقام الصفحات التي حددها المستخدم للطباعة. |
| [setPrintToFile](#setPrintToFile-boolean-) | يضبط قيمة تشير إلى ما إذا كان إخراج الطباعة يُرسل إلى ملف بدلاً من منفذ. |
| [setSelectedPages](#setSelectedPages-int:A-) | يضبط عدد الصفحات المحددة للطباعة. |
| [setToPage](#setToPage-int-) | يضبط رقم الصفحة الأخيرة للطباعة. |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

يُنشئ مثيلاً جديداً لفئة PrinterSettings.

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

يحصل على قيمة تشير إلى ما إذا كانت الطابعة تدعم الطباعة على الوجهين.

**Returns:**
قيمة منطقية

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

احصل على كائن Graphics2D

**Returns:**
كائن Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

احصل على كائن Graphics2D

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

**Returns:**
كائن Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
احصل على كائن Graphics2D

**Returns:**
كائن Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
احصل على كائن Graphics2D

**Returns:**
كائن Graphics2D

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

احصل على كائن مستنسخ

**Returns:**
كائن PdfPrinterSettings

### getCopies {#getCopies--}
```
public short getCopies()
```

يحصل على عدد النسخ من المستند للطباعة.

**Returns:**
عدد النسخ

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

يحصل على إعدادات الصفحة الافتراضية لهذه الطابعة.

**Returns:**
إعدادات الصفحة الافتراضية

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

يحصل على أو يضبط إعداد الطابعة للطباعة على الوجهين.

**Returns:**
قيمة int @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

يحصل على أو يضبط رقم الصفحة الأولى للطباعة.

**Returns:**
قيمة int

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

يحصل على أسماء جميع الطابعات المثبتة على الحاسوب.

**Returns:**
كائن {@code ArrayList<String>}

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

يحصل على الزاوية، بالدرجات، التي يتم فيها تدوير الوضع العمودي لإنتاج الوضع الأفقي.

**Returns:**
قيمة int

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

يحصل على الحد الأقصى لعدد النسخ التي تسمح الطابعة للمستخدم بطباعتها في آن واحد.

**Returns:**
قيمة int

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

يحصل على أو يضبط الحد الأقصى للصفحة FromPage أو ToPage التي يمكن اختيارها في مربع حوار الطباعة.

**Returns:**
قيمة int

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

يحصل على أو يضبط الحد الأدنى للصفحة FromPage أو ToPage التي يمكن اختيارها في مربع حوار الطباعة.

**Returns:**
قيمة int

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

يحصل على أحجام الورق التي تدعمها هذه الطابعة.

**Returns:**
كائن {@code ArrayList<PrintPaperSize> }

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

يحصل على صواني مصدر الورق المتاحة في الطابعة.

**Returns:**
كائن {@code ArrayList<PrintPaperSource> }

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

يحصل على أو يضبط اسم الطابعة المستخدمة.

**Returns:**
كائن سلسلة

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

يحصل على جميع الدقات التي تدعمها هذه الطابعة.

**Returns:**
كائن PrinterResolutionCollection

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

إرجاع كائن PrinterSettings

**Returns:**
كائن PrinterSettings

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

يحصل على أو يضبط اسم الملف عند الطباعة إلى ملف.

**Returns:**
كائن سلسلة

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

يحصل على أو يضبط أرقام الصفحات التي حددها المستخدم للطباعة.

**Returns:**
قيمة int @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

يحصل على عدد الصفحات المحددة للطباعة.

**Returns:**
مصفوفة int pagesList @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

يحصل على أو يضبط رقم الصفحة الأخيرة للطباعة.

**Returns:**
قيمة int

### isCollate {#isCollate--}
```
public boolean isCollate()
```

يحصل على أو يضبط قيمة تشير إلى ما إذا كان المستند المطبوع مرتبًا.

**Returns:**
قيمة منطقية

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

يحصل على قيمة تشير إلى ما إذا كانت خاصية PrinterName تعين الطابعة الافتراضية، باستثناء عندما يقوم المستخدم بتعيين PrinterName صراحةً.

**Returns:**
قيمة منطقية

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
يحصل على قيمة تشير إلى ما إذا كانت الطابعة تدعم DirectPrinting

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
يحصل على قيمة تشير إلى ما إذا كانت الطابعة تدعم DirectPrinting

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

يحصل على قيمة تشير إلى ما إذا كانت الطابعة جهاز رسم.

**Returns:**
قيمة منطقية

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

يحصل على قيمة تشير إلى ما إذا كان ناتج الطباعة يُرسل إلى ملف بدلاً من منفذ.

**Returns:**
قيمة منطقية

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

يحصل على قيمة تشير إلى ما إذا كانت هذه الطابعة تدعم الطباعة بالألوان.

**Returns:**
قيمة منطقية

### isValid {#isValid--}
```
public boolean isValid()
```

يحصل على قيمة تشير إلى ما إذا كانت خاصية PrinterName تعين طابعة صالحة.

**Returns:**
قيمة منطقية

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

يحصل على أو يضبط قيمة تشير إلى ما إذا كان المستند المطبوع مرتبًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

يضبط عدد نسخ المستند للطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عدد النسخ |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

يحصل على أو يضبط إعداد الطابعة للطباعة على الوجهين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

يحصل على أو يضبط رقم الصفحة الأولى للطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

يحصل على أو يضبط الحد الأقصى للصفحة FromPage أو ToPage التي يمكن اختيارها في مربع حوار الطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

يحصل على أو يضبط الحد الأدنى للصفحة FromPage أو ToPage التي يمكن اختيارها في مربع حوار الطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPrinterName {#setPrinterName-java.lang.String-}
يضبط اسم الطابعة المستخدمة.

### setPrintFileName {#setPrintFileName-java.lang.String-}
يضبط اسم الملف للطباعة.

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

يضبط أرقام الصفحات التي حددها المستخدم للطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر PdfPrintRange @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان إخراج الطباعة يُرسل إلى ملف بدلاً من منفذ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

يضبط عدد الصفحات المحددة للطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pagesList |  | مصفوفة int @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

يضبط رقم الصفحة الأخيرة للطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر PdfPrintRange @see PdfPrintRange |
