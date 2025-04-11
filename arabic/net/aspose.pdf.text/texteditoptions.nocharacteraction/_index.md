---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptionsNoCharacterAction enum. الإجراء الذي يجب اتخاذه إذا كانت الخط لا تحتوي على الحرف المطلوب
type: docs
weight: 10860
url: /ar/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

الإجراء الذي يجب اتخاذه إذا كانت الخط لا تحتوي على الحرف المطلوب

```csharp
public enum NoCharacterAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ThrowException | `0` | إلقاء استثناء |
| UseStandardFont | `1` | استبدال الخط بخط قياسي يحتوي على الحرف المطلوب |
| ReplaceAnyway | `2` | استبدال النص على أي حال دون استبدال الخط |
| ReplaceFonts | `3` | استبدال الخطوط حسب الحاجة لضمان عرض جميع الأحرف في النص. تتبع خوارزمية استبدال الخطوات التالية: 1. إذا قام المستخدم بتعيين خاصية الخط بشكل صريح، تحقق مما إذا كان الخط المحدد يمكنه عرض الأحرف المطلوبة. 2. إذا لم يتم تعيين خط محدد من قبل المستخدم، ابحث في الخطوط المضافة عبر [`Sources`](../fontrepository/sources/). 3. تحليل النص لتحديد أبجديته أو نصه واقتراح أسماء الخطوط وفقًا لذلك. حاول تحديد واستخدام هذه الخطوط من النظام. 4. كخيار احتياطي، ابحث في النظام عن أي خط قادر على عرض الأحرف المطلوبة. |
| UseCustomReplacementFont | `4` | استبدال الخط بخط الاستبدال المحدد |

### See Also

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)