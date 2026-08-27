---
title: "الفئة TextEditOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Text.TextEditOptions. تصف خيارات عمليات تحرير النص"
type: docs
weight: 11000
url: /ar/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

يصف خيارات عمليات تحرير النص.

```csharp
public sealed class TextEditOptions : TextOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | ينشئ نسخة جديدة من كائن `TextEditOptions` لأجل إذن تحويل اللغة المحدد. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | ينشئ نسخة جديدة من كائن `TextEditOptions` لوضع سلوك استبدال الخط المحدد. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | ينشئ نسخة جديدة من كائن `TextEditOptions` لوضع سلوك تحويل اللغة المحدد. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | ينشئ نسخة جديدة من كائن `TextEditOptions` لوضع سلوك عدم وجود أحرف المحدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | يحصل أو يعيّن القيمة التي تسمح باستخدام تحويل اللغة أثناء إضافة أو تحرير النص. true - سيتم تطبيق تحويل اللغة إذا لزم الأمر (القيمة الافتراضية). false - لن يتم تطبيق تحويل اللغة. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | يحصل على الوضع لمعالجة مسار القص للنص المُحرر. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | يحصل على الوضع الذي يحدد السلوك لسيناريوهات استبدال الخطوط. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | يحصل على الوضع الذي يحدد السلوك لسيناريوهات تحويل اللغة. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | يحصل أو يعيّن الوضع الذي يحدد السلوك في حال عدم احتواء الخطوط على الأحرف المطلوبة. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | يحصل أو يعيّن الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | يحصل أو يعيّن القيمة التي تسمح بالبحث عن تسطير النص على صفحة المستند المصدر. (مهمل) يرجى استخدام TextSearchOptions.SearchForTextRelatedGraphics بدلاً من ذلك. |

### انظر أيضًا

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


