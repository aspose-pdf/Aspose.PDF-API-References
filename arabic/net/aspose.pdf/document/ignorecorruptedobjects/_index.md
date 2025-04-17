---
title: Document.IgnoreCorruptedObjects
second_title: Aspose.PDF for .NET API Reference
description: خاصية الوثيقة. تحصل أو تضبط علم تجاهل الأخطاء في ملفات المصدر. عندما يتم نسخ الصفحات من الوثيقة المصدر إلى الوثيقة الوجهة، تتوقف عملية النسخ مع استثناء إذا كانت بعض الكائنات في ملفات المصدر تالفة عندما يكون هذا العلم خاطئًا. مثال  إذا تم تعيين هذا العلم إلى صحيح، فسيتم استبدال الكائنات التالفة بقيم فارغة. بشكل افتراضي صحيح.
type: docs
weight: 270
url: /ar/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Document.IgnoreCorruptedObjects property

تحصل أو تضبط علم تجاهل الأخطاء في ملفات المصدر. عندما يتم نسخ الصفحات من الوثيقة المصدر إلى الوثيقة الوجهة، تتوقف عملية النسخ مع استثناء إذا كانت بعض الكائنات في ملفات المصدر تالفة عندما يكون هذا العلم خاطئًا. مثال: dest.Pages.Add(src.Pages); إذا تم تعيين هذا العلم إلى صحيح، فسيتم استبدال الكائنات التالفة بقيم فارغة. بشكل افتراضي: صحيح.

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)