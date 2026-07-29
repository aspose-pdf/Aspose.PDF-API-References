---
title: "الفئة TextReplaceOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Text.TextReplaceOptions. تمثل خيارات استبدال النص"
type: docs
weight: 11190
url: /ar/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class

يمثل خيارات استبدال النص

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | ينشئ مثيلاً جديدًا لكائن `TextReplaceOptions` للإجراء المحدد بعد الاستبدال. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | ينشئ مثيلاً جديدًا لكائن `TextReplaceOptions` للنطاق المحدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | يحصل أو يعيّن قيمة تباعد الأسطر المستخدمة إذا تم إجبار تعديل الاستبدال على إنشاء سطر نص جديد. القيمة المتوقعة هي مضاعف حجم الخط للنص المستبدل. القيمة الافتراضية هي 1.2. |
| [FontSizeAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/fontsizeadjustmentaction/) { get; set; } | يحصل أو يعيّن السياسة لضبط حجم الخط ليتناسب مع الحدود المعرفة بواسطة [`Rectangle`](./rectangle/). |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تجاهل الفقرات المتميزة عند ضبط النص على الصفحة بعد استبدال النص. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | يعيّن أو يحصل على تعديل الموضع الأيسر للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [Rectangle](../../aspose.pdf.text/textreplaceoptions/rectangle/) { get; set; } | يحصل أو يعيّن المستطيل لتناسب النص بعد الاستبدال. |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | يحصل أو يعيّن الإجراء الذي سيتم بعد استبدال جزء النص ليصبح أقصر. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | يحصل أو يعيّن النطاق الذي يُطبق فيه عملية استبدال النص |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | يعيّن أو يحصل على تعديل الموضع الأيمن للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### انظر أيضًا

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


