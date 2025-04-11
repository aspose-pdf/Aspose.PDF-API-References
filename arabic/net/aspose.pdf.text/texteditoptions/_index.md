---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.TextEditOptions. تصف خيارات عمليات تحرير النص
type: docs
weight: 10820
url: /ar/net/aspose.pdf.text/texteditoptions/
---
## فئة TextEditOptions

تصف خيارات عمليات تحرير النص.

```csharp
public sealed class TextEditOptions : TextOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | يقوم بتهيئة مثيل جديد من كائن `TextEditOptions` لإذن تحويل اللغة المحدد. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | يقوم بتهيئة مثيل جديد من كائن `TextEditOptions` لوضع سلوك استبدال الخط المحدد. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | يقوم بتهيئة مثيل جديد من كائن `TextEditOptions` لوضع سلوك تحويل اللغة المحدد. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | يقوم بتهيئة مثيل جديد من كائن `TextEditOptions` لوضع سلوك عدم وجود حرف المحدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | يحصل أو يحدد القيمة التي تسمح باستخدام تحويل اللغة أثناء إضافة أو تحرير النص. true - سيتم تطبيق تحويل اللغة إذا لزم الأمر (القيمة الافتراضية). false - لن يتم تطبيق تحويل اللغة. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | يحصل على وضع معالجة مسار القص للنص المعدل. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | يحصل على وضع يحدد السلوك لسيناريوهات استبدال الخطوط. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | يحصل على وضع يحدد السلوك لسيناريوهات تحويل اللغة. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | يحصل أو يحدد الوضع الذي يحدد السلوك في حالة عدم احتواء الخطوط على الأحرف المطلوبة. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | يحصل أو يحدد الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | يحصل أو يحدد القيمة التي تسمح بالبحث عن تسطير النص على صفحة الوثيقة المصدر. (عفا عليها الزمن) يرجى استخدام TextSearchOptions.SearchForTextRelatedGraphics بدلاً من ذلك. |

### انظر أيضًا

* فئة [TextOptions](../textoptions/)
* مساحة الاسم [Aspose.Pdf.Text](../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../)