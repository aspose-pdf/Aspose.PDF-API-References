---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "عند تحويل ملف PDF (الذي عادةً ما يكون بتخطيط ثابت)، يحاول محرك التحويل إجراء تجميع وتحليل متعدد المستويات لاستعادة المستند الأصلي."
type: docs
weight: 1250
url: /ar/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

عند تحويل ملف PDF (الذي عادةً ما يكون بتخطيط ثابت)، يحاول محرك التحويل إجراء التجميع والتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج نتيجة بتخطيط تدفقي. هذه الخاصية تضبط ذلك التحويل لهذه أو لتلك الطريقة المرغوبة للتعرف على المحتوى.

## الحقول

| حقل | الوصف |
| --- | --- |
| [Fixed](#Fixed) | هذا الوضع سريع ومناسب للحفاظ إلى أقصى حد على مظهر الصفحات الأصلي، لكن للأسف العديد من قارئات EPUB لا تدعم xhtml مع تخطيط ثابت |
| [Flow](#Flow) | وضع التعرف الكامل، يحاول المحرك إجراء التجميع والتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج xhtml بتخطيط تدفق |
| [PdfFlow](#PdfFlow) | الفكرة الرئيسية لهذا التحويل تستند إلى حفظ الترتيب "الطبيعي" لتصيير المحتوى الذي يتشكل أثناء معالجة مستندات pdf. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | يعيد ثابت التعداد لهذا النوع بالاسم المحدد. |
| [values](#values--) | يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

هذا الوضع سريع ومناسب للحفاظ إلى أقصى حد على مظهر الصفحات الأصلي، لكن للأسف العديد من قارئات EPUB لا تدعم xhtml مع تخطيط ثابت

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

وضع التعرف الكامل، يحاول المحرك إجراء التجميع والتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج xhtml بتخطيط تدفق

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

الفكرة الرئيسية لهذا التحويل تستند إلى حفظ الترتيب "الطبيعي" لتصيير المحتوى الذي يتشكل أثناء معالجة مستندات pdf.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
يعيد ثابت التعداد لهذا النوع بالاسم المحدد.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه.

**Returns:**
مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه
