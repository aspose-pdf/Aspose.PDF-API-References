---
title: "التعداد HtmlSaveOptions.AntialiasingProcessingType"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "التعداد Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType. يصف هذا التعداد إجراءات مكافحة التعرج الممكنة أثناء التحويل."
type: docs
weight: 5700
url: /ar/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

يصف هذا التعداد إجراءات مكافحة التعرج الممكنة أثناء التحويل.

```csharp
public enum AntialiasingProcessingType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | لا توجد معالجة خاصة لمكافحة التعرج قيد الاستخدام. هذا خيار أمثل للأغلبية الساحقة من المستندات ولا يتطلب وقتًا إضافيًا أثناء التحويل. |
| TryCorrectResultHtml | `1` | في مثل هذه الحالة يحاول converter اكتشاف الأماكن التي تحتوي على عناصر رسومية خلفية متجاورة وتصحيح نتيجة HTML بطريقة ملائمة. يتيح هذا option تحسين نتيجة التصدير للمستندات التي تحتوي على خلفيات مكوّنة من عدة عناصر رسومية متجاورة (في مثل هذه المستندات عادةً ما تحاول عارضات PDF, مثل Acrobat Reader, تنعيم حدود العناصر أثناء العرض. باستخدام هذا option يحاكي converter سلوك عارضات PDF-renderers). يتيح هذا option تحسين تخطيط نتيجة التصدير لبعض المستندات المحددة (التي تستخدم مثل هذه الخلفيات المركبة)، لكنه يتطلب وقتًا إضافيًا للمعالجة (عادةً حوالي 10-15٪ من الوقت الإضافي). لذا لا يُنصح باستخدام هذا الوضع في الحالة العامة. |

### انظر أيضًا

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


