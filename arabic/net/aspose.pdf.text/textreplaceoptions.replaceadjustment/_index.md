---
title: "التعداد TextReplaceOptions.ReplaceAdjustment"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "التعداد Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment. يحدد الإجراء الذي سيُجرى بعد استبدال جزء من النص بجزء أقصر. None لا إجراء، قد يتداخل النص المستبدل مع باقي السطر. AdjustSpaceWidth يحاول تعديل المسافات بين الكلمات للحفاظ على طول السطر. WholeWordsHyphenation يحاول توزيع الكلمات بين أسطر الفقرة للحفاظ على حقل الفقرة الأيمن. ShiftRestOfLine ي shift باقي السطر وفقًا لتغيير طول النص؛ قد يتغير طول السطر. القيمة الافتراضية هي ShiftRestOfLine."
type: docs
weight: 11210
url: /ar/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

يحدد الإجراء الذي سيُجرى بعد استبدال جزء من النص بجزء أقصر. None - لا إجراء، قد يتداخل النص المستبدل مع باقي السطر؛ AdjustSpaceWidth - يحاول تعديل المسافات بين الكلمات للحفاظ على طول السطر؛ WholeWordsHyphenation - يحاول توزيع الكلمات بين أسطر الفقرة للحفاظ على الحقل الأيمن للفقرة؛ ShiftRestOfLine - يحرك باقي السطر وفقًا لتغيير طول النص، قد يتغير طول السطر؛ القيمة الافتراضية هي ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | لا إجراء، قد يتداخل النص المستبدل مع باقي السطر |
| AdjustSpaceWidth | `1` | يحاول تعديل الفراغات بين الكلمات للحفاظ على طول السطر |
| WholeWordsHyphenation | `2` | يحاول توزيع الكلمات بين أسطر الفقرة للحفاظ على الحقل الأيمن للفقرة |
| IsFormFillingMode | `4` | يحاول توزيع الكلمات في المساحة البيضاء المتاحة باستخدام عرض الفقرة. إذا تجاوز النص، سيتم إخفاؤه. |
| ShiftRestOfLine | `8` | (افتراضي) ينقل باقي السطر وفقًا لتغير طول النص، قد يتغير طول السطر |

### انظر أيضًا

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


