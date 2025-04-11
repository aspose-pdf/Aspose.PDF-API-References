---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode enum. يحدد أوضاعًا مختلفة يمكن استخدامها أثناء تحويل مستند PDF إلى نص. انظر فئة TextDevice
type: docs
weight: 10900
url: /ar/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumeration

يحدد أوضاعًا مختلفة يمكن استخدامها أثناء تحويل مستند PDF إلى نص. انظر !:فئة TextDevice.

```csharp
public enum TextFormattingMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Pure | `0` | يمثل محتوى PDF مع بعض روتينات التنسيق. |
| Raw | `1` | يمثل محتوى PDF كما هو، أي بدون تنسيق. |
| Flatten | `2` | يمثل محتوى PDF مع وضع أجزاء النص حسب إحداثياتها. إنه مشابه أساسًا لوضع "Raw". ولكن بينما يركز "Raw" على الحفاظ على هيكل أجزاء النص (العوامل) في المستند، يركز "Flatten" على الحفاظ على النص بالترتيب الذي يُقرأ به. |
| MemorySaving | `3` | استخراج مع توفير الذاكرة. إنه مشابه تقريبًا لوضع "Raw" ولكنه يعمل بشكل أسرع قليلاً ويستخدم ذاكرة أقل. |

### See Also

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)