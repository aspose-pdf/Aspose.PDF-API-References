---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMode enum. يحدد وضع التحقق لعمليات التحقق من توقيع PDF
type: docs
weight: 10060
url: /ar/net/aspose.pdf.security/validationmode/
---
## ValidationMode enumeration

يحدد وضع التحقق لعمليات التحقق من توقيع PDF.

```csharp
public enum ValidationMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | يمثل وضعًا لا يتم فيه إجراء التحقق. |
| OnlyCheck | `1` | يمثل الوضع الذي يتم فيه إجراء التحقق، لكن نتيجته لا تؤثر على تحقق التوقيع الرقمي. يمكنك التحقق من نتيجة التحقق بنفسك. |
| Strict | `2` | يمثل الوضع الذي يتم فيه إجراء التحقق وتؤثر نتيجته على تحقق التوقيع الرقمي. إذا لم يكن بالإمكان التحقق من الشهادة، فسيعتبر التوقيع الرقمي غير صالح. يمكنك التحقق من نتيجة التحقق بنفسك. |

### See Also

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)