---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل أنواع استراتيجيات التعرف على العناوين."
type: docs
weight: 30
url: /ar/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

يمثل أنواع استراتيجيات التعرف على العناوين.

## الحقول

| حقل | الوصف |
| --- | --- |
| [Auto](#Auto) | يوفر اختيارًا تلقائيًا لاستراتيجية التعرف على العناوين. هذا هو الخيار الافتراضي. إذا كان المستند يحتوي على إشارات مرجعية، سيتم اختيار استراتيجية {@link HeadingRecognitionStrategy#Outlines}، وإلا سيتم اختيار {@link HeadingRecognitionStrategy#Heuristic} |
| [Heuristic](#Heuristic) | يمثل استراتيجية التعرف على العناوين عبر قواعد الاستدلال وإحصائيات حجم الخط. |
| [None](#None) | لا تتعرف على العناوين. قد يكون هذا الخيار مفيدًا في المستندات ذات التنسيق المعقد. |
| [Outlines](#Outlines) | يمثل استراتيجية التعرف على العناوين عبر المخططات. |

### Auto {#Auto}
```
public static final int Auto
```

يوفر اختيارًا تلقائيًا لاستراتيجية التعرف على العناوين. هذا هو الخيار الافتراضي. إذا كان المستند يحتوي على إشارات مرجعية، سيتم اختيار استراتيجية {@link HeadingRecognitionStrategy#Outlines}، وإلا سيتم اختيار {@link HeadingRecognitionStrategy#Heuristic}

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

يمثل استراتيجية التعرف على العناوين عبر قواعد الاستدلال وإحصائيات حجم الخط.

### None {#None}
```
public static final int None
```

لا تتعرف على العناوين. قد يكون هذا الخيار مفيدًا في المستندات ذات التنسيق المعقد.

### Outlines {#Outlines}
```
public static final int Outlines
```

يمثل استراتيجية التعرف على العناوين عبر المخططات.
