---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة خيار حفظ المستند بتنسيق markdown."
type: docs
weight: 60
url: /ar/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

يمثل فئة خيار حفظ المستند بتنسيق markdown.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | ينشئ خيارًا لإنشاء نسخة لحفظ مستند بتنسيق markdown. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | احصل على أو اضبط منطقة مستطيلة لاستخراج المحتوى إلى markdown. |
| [getEmphasisStyle](#getEmphasisStyle--) | يحصل أو يضبط نمط التأكيد للمستند المُنشأ. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | يحصل على ويضبط خاصية تشير إلى ما إذا كان يجب استخراج الرسومات المتجهية. |
| [getHeadingLevels](#getHeadingLevels--) | يحدد مستويات العناوين المتوقعة لاستخدامها في استراتيجية التعرف على رؤوس حجم الخط. إذا تم تعيين قيمة هذه الخاصية، فستُختار استراتيجية التعرف على العناوين {@link HeadingRecognitionStrategy#Heuristic} عندما يتم تعيين استراتيجيات {@link HeadingRecognitionStrategy#Auto} حتى إذا كان المستند يحتوي على إشارات مرجعية. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | يحصل على أو يضبط استراتيجية التعرف على العناوين. |
| [getHeadingStyle](#getHeadingStyle--) | يحصل على أو يضبط نمط العنوان للمستند المُولد. |
| [getLineBreakStyle](#getLineBreakStyle--) | يحصل على أو يضبط نمط فاصل السطر للمستند المُولد. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | يحصل على ويضبط اسم الدليل لحفظ موارد المستند مثل الصور. إذا لم يتم تحديد القيمة، فستُكتب الصور في نفس الدليل الذي يوجد فيه ملف الـ markdown نفسه. هذا ليس مسارًا، إنه مجرد اسم! سيتم إنشاء هذا الدليل تلقائيًا في الدليل الذي يحتوي على ملف الـ markdown المحفوظ. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | يحصل على ويضبط اسم الدليل لحفظ موارد المستند مثل الصور. سيتم إنشاء هذا الدليل تلقائيًا في الدليل الذي يحتوي على ملف الـ markdown المحفوظ. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | يحصل على ويضبط السماح بتحويل النص السفلي والعلوي. القيمة الافتراضية هي true. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | يحصل على ويضبط السماح باستخدام وسم img لإدراج الصور إلى يسار أو يمين النص. في هذه الحالة، سيُلف النص حول الصورة في عارض الـ markdown. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | احصل على أو اضبط منطقة مستطيلة لاستخراج المحتوى إلى markdown. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | يحصل أو يضبط نمط التأكيد للمستند المُنشأ. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | يحصل على ويضبط خاصية تشير إلى ما إذا كان يجب استخراج الرسومات المتجهية. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | يحدد مستويات العناوين المتوقعة لاستخدامها في استراتيجية التعرف على رؤوس حجم الخط. إذا تم تعيين قيمة هذه الخاصية، فستُختار استراتيجية التعرف على العناوين {@link HeadingRecognitionStrategy#Heuristic} عندما يتم تعيين استراتيجيات {@link HeadingRecognitionStrategy#Auto} حتى إذا كان المستند يحتوي على إشارات مرجعية. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | يحصل على أو يضبط استراتيجية التعرف على العناوين. |
| [setHeadingStyle](#setHeadingStyle-int-) | يحصل على أو يضبط نمط العنوان للمستند المُولد. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | يحصل على أو يضبط نمط فاصل السطر للمستند المُولد. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | يحصل على ويضبط اسم الدليل لحفظ موارد المستند مثل الصور. إذا لم يتم تحديد القيمة، فستُكتب الصور في نفس الدليل الذي يوجد فيه ملف الـ markdown نفسه. هذا ليس مسارًا، إنه مجرد اسم! سيتم إنشاء هذا الدليل تلقائيًا في الدليل الذي يحتوي على ملف الـ markdown المحفوظ. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | يحصل على ويضبط اسم الدليل لحفظ موارد المستند مثل الصور. سيتم إنشاء هذا الدليل تلقائيًا في الدليل الذي يحتوي على ملف الـ markdown المحفوظ. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | يحصل على ويضبط السماح بتحويل النص السفلي والعلوي. القيمة الافتراضية هي true. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | يحصل على ويضبط السماح باستخدام وسم img لإدراج الصور إلى يسار أو يمين النص. في هذه الحالة، سيُلف النص حول الصورة في عارض الـ markdown. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

ينشئ خيارًا لإنشاء نسخة لحفظ مستند بتنسيق markdown.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

احصل على أو اضبط منطقة مستطيلة لاستخراج المحتوى إلى markdown.

**Returns:**
مثيل Rectangle

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

يحصل أو يضبط نمط التأكيد للمستند المُنشأ.

**Returns:**
عنصر EmphasisStyle

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

يحصل على ويضبط خاصية تشير إلى ما إذا كان يجب استخراج الرسومات المتجهية.

**Returns:**
قيمة منطقية

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

يحدد مستويات العناوين المتوقعة لاستخدامها في استراتيجية التعرف على رؤوس حجم الخط. إذا تم تعيين قيمة هذه الخاصية، فستُختار استراتيجية التعرف على العناوين {@link HeadingRecognitionStrategy#Heuristic} عندما يتم تعيين استراتيجيات {@link HeadingRecognitionStrategy#Auto} حتى إذا كان المستند يحتوي على إشارات مرجعية.

**Returns:**
مثيل HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

يحصل على أو يضبط استراتيجية التعرف على العناوين.

**Returns:**
عنصر HeadingRecognitionStrategy

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

يحصل على أو يضبط نمط العنوان للمستند المُولد.

**Returns:**
عنصر HeadingStyle

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

يحصل على أو يضبط نمط فاصل السطر للمستند المُولد.

**Returns:**
عنصر LineBreakStyle

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

يحصل على ويضبط اسم الدليل لحفظ موارد المستند مثل الصور. إذا لم يتم تحديد القيمة، فستُكتب الصور في نفس الدليل الذي يوجد فيه ملف الـ markdown نفسه. هذا ليس مسارًا، إنه مجرد اسم! سيتم إنشاء هذا الدليل تلقائيًا في الدليل الذي يحتوي على ملف الـ markdown المحفوظ.

**Returns:**
قيمة سلسلة

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

يحصل على ويضبط اسم الدليل لحفظ موارد المستند مثل الصور. سيتم إنشاء هذا الدليل تلقائيًا في الدليل الذي يحتوي على ملف الـ markdown المحفوظ.

**Returns:**
قيمة سلسلة

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

يحصل على ويضبط السماح بتحويل النص السفلي والعلوي. القيمة الافتراضية هي true.

**Returns:**
قيمة منطقية

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

يحصل على ويضبط السماح باستخدام وسم img لإدراج الصور إلى يسار أو يمين النص. في هذه الحالة، سيُلف النص حول الصورة في عارض الـ markdown.

**Returns:**
قيمة منطقية

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
احصل على أو اضبط منطقة مستطيلة لاستخراج المحتوى إلى markdown.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

يحصل أو يضبط نمط التأكيد للمستند المُنشأ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر EmphasisStyle |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

يحصل على ويضبط خاصية تشير إلى ما إذا كان يجب استخراج الرسومات المتجهية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
يحدد مستويات العناوين المتوقعة لاستخدامها في استراتيجية التعرف على رؤوس حجم الخط. إذا تم تعيين قيمة هذه الخاصية، فستُختار استراتيجية التعرف على العناوين {@link HeadingRecognitionStrategy#Heuristic} عندما يتم تعيين استراتيجيات {@link HeadingRecognitionStrategy#Auto} حتى إذا كان المستند يحتوي على إشارات مرجعية.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

يحصل على أو يضبط استراتيجية التعرف على العناوين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر HeadingRecognitionStrategy |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

يحصل على أو يضبط نمط العنوان للمستند المُولد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر HeadingStyle |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

يحصل على أو يضبط نمط فاصل السطر للمستند المُولد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر LineBreakStyle |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
يحصل على ويضبط اسم الدليل لحفظ موارد المستند مثل الصور. إذا لم يتم تحديد القيمة، فستُكتب الصور في نفس الدليل الذي يوجد فيه ملف الـ markdown نفسه. هذا ليس مسارًا، إنه مجرد اسم! سيتم إنشاء هذا الدليل تلقائيًا في الدليل الذي يحتوي على ملف الـ markdown المحفوظ.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
يحصل على ويضبط اسم الدليل لحفظ موارد المستند مثل الصور. سيتم إنشاء هذا الدليل تلقائيًا في الدليل الذي يحتوي على ملف الـ markdown المحفوظ.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

يحصل على ويضبط السماح بتحويل النص السفلي والعلوي. القيمة الافتراضية هي true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

يحصل على ويضبط السماح باستخدام وسم img لإدراج الصور إلى يسار أو يمين النص. في هذه الحالة، سيُلف النص حول الصورة في عارض الـ markdown.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
