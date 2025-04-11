---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.TextReplaceOptions. تمثل خيارات استبدال النص
type: docs
weight: 11010
url: /ar/net/aspose.pdf.text/textreplaceoptions/
---
## Class TextReplaceOptions

تمثل خيارات استبدال النص

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | يقوم بتهيئة مثيل جديد من كائن `TextReplaceOptions` للعملية المحددة بعد الاستبدال. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | يقوم بتهيئة مثيل جديد من كائن `TextReplaceOptions` للنطاق المحدد. |

## Properties

| Name | Description |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | يحصل أو يحدد قيمة تباعد الأسطر التي تستخدم إذا تم فرض تعديل الاستبدال لإنشاء سطر جديد من النص. القيمة المتوقعة هي مضاعف لحجم خط النص المستبدل. الافتراضي هو 1.2. |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | يحصل أو يحدد قيمة تشير إلى ما إذا كان يجب تجاهل الفقرات المتميزة عند ضبط النص على الصفحة بعد استبدال النص. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | يحدد أو يحصل على تعديل الموضع الأيسر للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | يحصل أو يحدد إجراء سيتم تنفيذه بعد استبدال جزء النص بنص أقصر. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | يحصل أو يحدد نطاق حيث يتم تطبيق عملية استبدال النص |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | يحدد أو يحصل على تعديل الموضع الأيمن للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### See Also

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)