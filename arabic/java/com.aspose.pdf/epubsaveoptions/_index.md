---
title: "EpubSaveOptions"
linktitle: "EpubSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "خيارات الحفظ للتصدير إلى تنسيق EPUB"
type: docs
weight: 1240
url: /ar/java/com.aspose.pdf/epubsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.EpubSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.EpubSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.EpubSaveOptions

```
public class EpubSaveOptions extends UnifiedSaveOptions
```

خيارات الحفظ للتصدير إلى تنسيق EPUB

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [EpubSaveOptions](#EpubSaveOptions--) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getContentRecognitionMode](#getContentRecognitionMode--) | عند تحويل ملف PDF (الذي عادةً ما يكون بتخطيط ثابت)، يحاول محرك التحويل إجراء التجميع والتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج نتيجة بتخطيط تدفقي. هذه الخاصية تضبط ذلك التحويل لهذه أو لتلك الطريقة المرغوبة للتعرف على المحتوى. |
| [getTitle](#getTitle--) | يحصل أو يعيّن عنوان مستند EPUB. |
| [setContentRecognitionMode](#setContentRecognitionMode-com.aspose.pdf.EpubSaveOptions.RecognitionMode-) | عند تحويل ملف PDF (الذي عادةً ما يكون بتخطيط ثابت)، يحاول محرك التحويل إجراء التجميع والتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج النتيجة بتخطيط تدفّقي. |
| [setTitle](#setTitle-java.lang.String-) | يحصل أو يعيّن عنوان مستند EPUB. |

### EpubSaveOptions {#EpubSaveOptions--}
```
public EpubSaveOptions()
```

منشئ

### getContentRecognitionMode {#getContentRecognitionMode--}
```
public EpubSaveOptions.RecognitionMode getContentRecognitionMode()
```

عند تحويل ملف PDF (الذي عادةً ما يكون بتخطيط ثابت)، يحاول محرك التحويل إجراء التجميع والتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج نتيجة بتخطيط تدفقي. هذه الخاصية تضبط ذلك التحويل لهذه أو لتلك الطريقة المرغوبة للتعرف على المحتوى.

**Returns:**
عنصر RecognitionMode @see RecognitionMode

### getTitle {#getTitle--}
```
public final String getTitle()
```

يحصل أو يعيّن عنوان مستند EPUB.

**Returns:**
قيمة سلسلة

### setContentRecognitionMode {#setContentRecognitionMode-com.aspose.pdf.EpubSaveOptions.RecognitionMode-}
عند تحويل ملف PDF (الذي عادةً ما يكون بتخطيط ثابت)، يحاول محرك التحويل إجراء التجميع والتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج النتيجة بتخطيط تدفّقي.

### setTitle {#setTitle-java.lang.String-}
يحصل أو يعيّن عنوان مستند EPUB.
