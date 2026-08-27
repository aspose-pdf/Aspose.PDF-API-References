---
title: "التعداد TextEditOptions.NoCharacterAction"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "التعداد Aspose.Pdf.Text.TextEditOptionsNoCharacterAction. الإجراء الذي يُنفّذ إذا كان الخط لا يحتوي على الحرف المطلوب."
type: docs
weight: 11040
url: /ar/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

الإجراء الذي يجب تنفيذه إذا لم يحتوي الخط على الحرف المطلوب

```csharp
public enum NoCharacterAction
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| ThrowException | `0` | إلقاء استثناء |
| UseStandardFont | `1` | استبدال الخط إلى خط قياسي يحتوي على الحرف المطلوب |
| ReplaceAnyway | `2` | استبدال النص على أي حال دون استبدال الخط |
| ReplaceFonts | `3` | يستبدل الخطوط حسب الحاجة لضمان إمكانية عرض جميع الأحرف في النص. يتبع خوارزمية استبدال الخطوط الخطوات التالية: 1. إذا قام المستخدم بتعيين خاصية Font صراحةً، تحقق مما إذا كان الخط المحدد يمكنه عرض الأحرف المطلوبة. 2. إذا لم يتم تعيين خط من قبل المستخدم، ابحث في الخطوط المضافة عبر [`Sources`](../fontrepository/sources/). 3. حلل النص لتحديد أبجديته أو خطه واقترح أسماء الخطوط وفقًا لذلك. حاول العثور على هذه الخطوط واستخدامها من النظام. 4. كإجراء احتياطي، ابحث في النظام عن أي خط قادر على عرض الأحرف المطلوبة. |
| UseCustomReplacementFont | `4` | استبدل الخط إلى الخط البديل المحدد |

### انظر أيضًا

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


