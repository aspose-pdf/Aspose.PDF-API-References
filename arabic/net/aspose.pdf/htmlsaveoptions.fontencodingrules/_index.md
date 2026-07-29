---
title: "تعداد HtmlSaveOptions.FontEncodingRules"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "تعداد Aspose.Pdf.HtmlSaveOptionsFontEncodingRules. يحدد هذا التعداد القواعد التي تضبط منطق الترميز"
type: docs
weight: 5750
url: /ar/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

هذا التعداد يحدد القواعد التي تضبط منطق الترميز

```csharp
public enum FontEncodingRules : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Default | `0` | اترك منطق الترميز "كما هو" - وفقًا لمواصفات PDF |
| DecreaseToUnicodePriorityLevel | `1` | يُعد ToUnicode آلية خاصة تساعد على فك ترميز الرموز المدخلة إلى رموز Unicode. وفقًا للمواصفات يجب استخدامه كأول آلية للحصول على رموز Unicode للرمز المدخل المحدد. لكن بعض المستندات تحتوي على خطوط غير قياسية ولتحويل هذه المستندات بشكل صحيح قد يكون من الضروري خفض أولوية ToUnicode واستخدام آليات أخرى لفك ترميز الرموز المدخلة. |

### انظر أيضًا

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


