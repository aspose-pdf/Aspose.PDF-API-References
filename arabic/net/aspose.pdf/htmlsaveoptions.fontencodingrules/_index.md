---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontEncodingRules enum. هذه التعداد يحدد القواعد التي تضبط منطق الترميز
type: docs
weight: 5620
url: /ar/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

هذه التعداد يحدد القواعد التي تضبط منطق الترميز

```csharp
public enum FontEncodingRules : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | `0` | اترك منطق الترميز "كما هو" - وفقًا لمواصفات PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode هو آلية خاصة تساعد في فك تشفير الرموز المدخلة إلى رموز يونيكود. وفقًا للمواصفات، يجب استخدامه أولاً من جميع الآليات للحصول على رموز يونيكود للرمز المدخل المحدد. ولكن بعض الوثائق تحتوي على خطوط غير قياسية ولتحويل هذه الوثائق بشكل صحيح قد يكون من الضروري تقليل أولوية ToUnicode واستخدام آليات أخرى لفك تشفير الرموز المدخلة. |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)