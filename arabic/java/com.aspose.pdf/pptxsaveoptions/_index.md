---
title: "PptxSaveOptions"
linktitle: "PptxSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "خيارات الحفظ للتصدير إلى صيغة SVG."
type: docs
weight: 3950
url: /ar/java/com.aspose.pdf/pptxsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.PptxSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.PptxSaveOptions

```
public class PptxSaveOptions extends UnifiedSaveOptions
```

خيارات الحفظ للتصدير إلى صيغة SVG.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PptxSaveOptions](#PptxSaveOptions--) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> يمكن استخدام هذا المعالج للتعامل مع أحداث تقدم التحويل، على سبيل المثال يمكن استخدامه لإظهار شريط التقدم أو رسائل حول عدد الصفحات المعالجة الحالية، مثال على شفرة المعالج التي تُظهر التقدم في وحدة التحكم هو : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre> |
| [getImageResolution](#getImageResolution--) | يحصل أو يضبط دقة الصورة (dpi). القيمة الافتراضية هي 192 dpi. |
| [getSeparateImages](#getSeparateImages--) | إذا تم تعيينه إلى true فستُفصل الصور عن جميع الرسومات الأخرى. |
| [getSlidesAsImages](#getSlidesAsImages--) | إذا تم تعيينه إلى true فسيتم التعرف على جميع المحتوى كصور (واحدة لكل صفحة). |
| [isOptimizeTextBoxes](#isOptimizeTextBoxes--) | يقوم بتبديل التعرف على أعمدة النص. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | يمكن استخدام هذا المعالج لمعالجة أحداث تقدم التحويل على سبيل المثال. |
| [setImageResolution](#setImageResolution-int-) | يحصل أو يضبط دقة الصورة (dpi). القيمة الافتراضية هي 192 dpi. |
| [setOptimizeTextBoxes](#setOptimizeTextBoxes-boolean-) | يقوم بتبديل التعرف على أعمدة النص. |
| [setSeparateImages](#setSeparateImages-boolean-) | إذا تم تعيينه إلى true فستُفصل الصور عن جميع الرسومات الأخرى. |
| [setSlidesAsImages](#setSlidesAsImages-boolean-) | إذا تم تعيينه إلى true فسيتم التعرف على جميع المحتوى كصور (واحدة لكل صفحة). |

### PptxSaveOptions {#PptxSaveOptions--}
```
public PptxSaveOptions()
```

منشئ

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> يمكن استخدام هذا المعالج للتعامل مع أحداث تقدم التحويل، على سبيل المثال يمكن استخدامه لإظهار شريط التقدم أو رسائل حول عدد الصفحات المعالجة الحالية، مثال على شفرة المعالج التي تُظهر التقدم في وحدة التحكم هو : </p><hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("input.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole)); doc.save("output.html", saveOptions); } public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(string.Format("{0} - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(string.Format("{0} - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(string.Format("{0} - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(string.Format("{0} - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString())); break; default: break; } } </pre>

**Returns:**
مثيل ConversionProgressEventHandler

### getImageResolution {#getImageResolution--}
```
public final int getImageResolution()
```

يحصل أو يضبط دقة الصورة (dpi). القيمة الافتراضية هي 192 dpi.

**Returns:**
قيمة int

### getSeparateImages {#getSeparateImages--}
```
public boolean getSeparateImages()
```

إذا تم تعيينه إلى true فستُفصل الصور عن جميع الرسومات الأخرى.

**Returns:**
قيمة منطقية

### getSlidesAsImages {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```

إذا تم تعيينه إلى true فسيتم التعرف على جميع المحتوى كصور (واحدة لكل صفحة).

**Returns:**
قيمة منطقية

### isOptimizeTextBoxes {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```

يقوم بتبديل التعرف على أعمدة النص.

**Returns:**
قيمة منطقية

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
يمكن استخدام هذا المعالج لمعالجة أحداث تقدم التحويل على سبيل المثال.

### setImageResolution {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```

يحصل أو يضبط دقة الصورة (dpi). القيمة الافتراضية هي 192 dpi.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setOptimizeTextBoxes {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```

يقوم بتبديل التعرف على أعمدة النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSeparateImages {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```

إذا تم تعيينه إلى true فستُفصل الصور عن جميع الرسومات الأخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSlidesAsImages {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```

إذا تم تعيينه إلى true فسيتم التعرف على جميع المحتوى كصور (واحدة لكل صفحة).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
