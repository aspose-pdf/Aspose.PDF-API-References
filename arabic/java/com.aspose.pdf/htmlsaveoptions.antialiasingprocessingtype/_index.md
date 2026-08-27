---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "هذا التعداد يصف إجراءات مكافحة التعرجات الممكنة أثناء التحويل."
type: docs
weight: 2000
url: /ar/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

هذا التعداد يصف إجراءات مكافحة التعرجات الممكنة أثناء التحويل.

## الحقول

| حقل | الوصف |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | لا توجد معالجة مضادة للتنعيم خاصة قيد الاستخدام. هذا خيار أمثل لغالبية المستندات الكبيرة ولا يتطلب وقتًا إضافيًا أثناء التحويل. |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | في هذه الحالة يحاول المحول اكتشاف الأماكن التي تحتوي على عناصر رسومية خلفية متجاورة وتصحيح نتيجة HTML بطريقة ملائمة. يتيح هذا الخيار تحسين نتيجة التصدير للمستندات التي تحتوي على خلفيات مكوّنة من عدة عناصر رسومية متجاورة (في مثل هذه المستندات، عادةً ما تحاول عارضات PDF، مثل Acrobat Reader، تنعيم حدود العناصر أثناء العرض). باستخدام هذا الخيار يقلّد المحول سلوك عارضات PDF. يتيح هذا الخيار تحسين تخطيط نتيجة التصدير لبعض المستندات المحددة (التي تستخدم خلفيات مركبة)، لكنه يتطلب وقتًا إضافيًا للمعالجة (عادةً حوالي 10-15٪ من الوقت الإضافي). لذلك لا يُنصح باستخدام هذا الوضع في الحالات العامة. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

لا توجد معالجة مضادة للتنعيم خاصة قيد الاستخدام. هذا خيار أمثل لغالبية المستندات الكبيرة ولا يتطلب وقتًا إضافيًا أثناء التحويل.

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

في هذه الحالة يحاول المحول اكتشاف الأماكن التي تحتوي على عناصر رسومية خلفية متجاورة وتصحيح نتيجة HTML بطريقة ملائمة. يتيح هذا الخيار تحسين نتيجة التصدير للمستندات التي تحتوي على خلفيات مكوّنة من عدة عناصر رسومية متجاورة (في مثل هذه المستندات، عادةً ما تحاول عارضات PDF، مثل Acrobat Reader، تنعيم حدود العناصر أثناء العرض). باستخدام هذا الخيار يقلّد المحول سلوك عارضات PDF. يتيح هذا الخيار تحسين تخطيط نتيجة التصدير لبعض المستندات المحددة (التي تستخدم خلفيات مركبة)، لكنه يتطلب وقتًا إضافيًا للمعالجة (عادةً حوالي 10-15٪ من الوقت الإضافي). لذلك لا يُنصح باستخدام هذا الوضع في الحالات العامة.
