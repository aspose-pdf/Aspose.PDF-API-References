---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType enum. يصف هذا التعداد التدابير الممكنة لمكافحة التعرج أثناء التحويل
type: docs
weight: 5570
url: /ar/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

يصف هذا التعداد التدابير الممكنة لمكافحة التعرج أثناء التحويل

```csharp
public enum AntialiasingProcessingType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | لا يتم استخدام معالجة خاصة لمكافحة التعرج. هذه هي الخيار الأمثل للأغلبية الساحقة من الوثائق ولا تتطلب وقتًا إضافيًا أثناء التحويل |
| TryCorrectResultHtml | `1` | في هذه الحالة، يحاول المحول اكتشاف الأماكن التي تحتوي على عناصر رسومية خلفية متجاورة وتصحيح HTML الناتج بطريقة ذات صلة. يتيح هذا الخيار تحسين نتيجة التصدير للوثائق التي تحتوي على خلفيات مبنية من عدة عناصر رسومية متجاورة (بالنسبة لمثل هذه الوثائق، عادةً ما تحاول عارضات PDF، مثل Acrobat Reader، تنعيم حدود العناصر أثناء العرض. مع هذا الخيار، يقلد المحول سلوك عارضات PDF. يتيح هذا الخيار تحسين تخطيط نتيجة التصدير لبعض الوثائق المحددة (التي تستخدم مثل هذه الخلفيات المركبة)، ولكنه يتطلب وقتًا إضافيًا للمعالجة (عادة حوالي 10-15% من الوقت الإضافي). لذلك، فإن استخدام هذا الوضع بشكل عام غير موصى به. |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)