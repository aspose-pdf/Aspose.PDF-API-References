---
title: "التعداد TextExtractionOptions.TextFormattingMode"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "التعداد Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode. يحدد أوضاعًا مختلفة يمكن استخدامها أثناء تحويل مستند pdf إلى نص. راجع فئة TextDevice."
type: docs
weight: 11080
url: /ar/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumeration

يحدد أوضاعًا مختلفة يمكن استخدامها أثناء تحويل مستند pdf إلى نص. راجع الفئة !:TextDevice.

```csharp
public enum TextFormattingMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Pure | `0` | يمثل محتوى pdf مع قليل من روتينات التنسيق. |
| Raw | `1` | يمثل محتوى pdf كما هو، أي بدون تنسيق. |
| Flatten | `2` | يمثل محتوى pdf مع تموضع أجزاء النص وفقًا لإحداثياتها. هو في الأساس مشابه لوضع \"Raw\". لكن بينما يركز \"Raw\" على الحفاظ على بنية أجزاء النص (العوامل) في المستند، يركز \"Flatten\" على إبقاء النص بالترتيب الذي يُقرأ به. |
| MemorySaving | `3` | استخراج مع توفير الذاكرة. هو تقريبًا نفس وضع 'Raw' لكنه يعمل أسرع قليلًا ويستخدم ذاكرة أقل. |

### انظر أيضًا

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


