---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment enum. يحدد الإجراء الذي سيتم اتخاذه بعد استبدال جزء النص بأكثر اختصارًا. None - لا يوجد إجراء، النص المستبدل قد يتداخل مع بقية السطر؛ AdjustSpaceWidth - يحاول ضبط المسافات بين الكلمات للحفاظ على طول السطر؛ WholeWordsHyphenation - يحاول توزيع الكلمات بين أسطر الفقرة للحفاظ على الحقل الصحيح للفقرة؛ ShiftRestOfLine - يحرك بقية السطر وفقًا لتغيير طول النص، قد يتغير طول السطر؛ القيمة الافتراضية هي ShiftRestOfLine.
type: docs
weight: 11020
url: /ar/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

يحدد الإجراء الذي سيتم اتخاذه بعد استبدال جزء النص بأكثر اختصارًا. None - لا يوجد إجراء، النص المستبدل قد يتداخل مع بقية السطر؛ AdjustSpaceWidth - يحاول ضبط المسافات بين الكلمات للحفاظ على طول السطر؛ WholeWordsHyphenation - يحاول توزيع الكلمات بين أسطر الفقرة للحفاظ على الحقل الصحيح للفقرة؛ ShiftRestOfLine - يحرك بقية السطر وفقًا لتغيير طول النص، قد يتغير طول السطر؛ القيمة الافتراضية هي ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | لا يوجد إجراء، النص المستبدل قد يتداخل مع بقية السطر |
| AdjustSpaceWidth | `1` | يحاول ضبط المسافات بين الكلمات للحفاظ على طول السطر |
| WholeWordsHyphenation | `2` | يحاول توزيع الكلمات بين أسطر الفقرة للحفاظ على الحقل الصحيح للفقرة |
| IsFormFillingMode | `4` | يحاول نشر الكلمات في المساحة البيضاء المتاحة باستخدام عرض الفقرة. إذا تجاوز النص، سيتم إخفاؤه. |
| ShiftRestOfLine | `8` | (افتراضي) يحرك بقية السطر وفقًا لتغيير طول النص، قد يتغير طول السطر |

### See Also

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)