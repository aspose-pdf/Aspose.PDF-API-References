---
title: TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF لمرجع .NET API
description: يحدد الإجراء الذي سيتم اتخاذه بعد استبدال جزء النص بمزيد من الاختصار . بلا - لا يوجد إجراء  قد يتداخل النص المستبدل مع بقية السطر AdjustSpaceWidth - يحاول ضبط المسافات بين الكلمات للحفاظ على طول السطر WordsHyphenation - يحاول توزيع الكلمات بين سطور الفقرة للاحتفاظ بالحقل الأيمن للفقرة ShiftRestOfLine - يبدل باقي السطر وفقًا لتغيير طول النص  ويمكن تغيير طول السطر القيمة الافتراضية هي ShiftRestOfLine.
type: docs
weight: 7180
url: /ar/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

يحدد الإجراء الذي سيتم اتخاذه بعد استبدال جزء النص بمزيد من الاختصار . بلا - لا يوجد إجراء ، قد يتداخل النص المستبدل مع بقية السطر AdjustSpaceWidth - يحاول ضبط المسافات بين الكلمات للحفاظ على طول السطر WordsHyphenation - يحاول توزيع الكلمات بين سطور الفقرة للاحتفاظ بالحقل الأيمن للفقرة ShiftRestOfLine - يبدل باقي السطر وفقًا لتغيير طول النص ، ويمكن تغيير طول السطر القيمة الافتراضية هي ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| None | `0` | لا يوجد إجراء ، فقد يتداخل النص المُستبدل مع باقي السطر |
| AdjustSpaceWidth | `1` | يحاول ضبط المسافات بين الكلمات للحفاظ على طول السطر |
| WholeWordsHyphenation | `2` | يحاول توزيع الكلمات بين سطور الفقرة للاحتفاظ بالمجال الصحيح للفقرة |
| ShiftRestOfLine | `4` | (افتراضي) يغير باقي السطر وفقًا لتغيير طول النص ، ويمكن تغيير طول السطر |

### أنظر أيضا

* class [TextReplaceOptions](../textreplaceoptions)
* مساحة الاسم [Aspose.Pdf.Text](../../aspose.pdf.text)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->