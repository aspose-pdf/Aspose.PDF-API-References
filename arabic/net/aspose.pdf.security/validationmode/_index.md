---
title: "تعداد ValidationMode"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "تعداد Aspose.Pdf.Security.ValidationMode. يحدد وضع التحقق لعمليات التحقق من توقيع PDF"
type: docs
weight: 10240
url: /ar/net/aspose.pdf.security/validationmode/
---
## ValidationMode enumeration

يحدد وضع التحقق لعمليات التحقق من توقيع PDF.

```csharp
public enum ValidationMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | يمثل وضعًا لا يتم فيه إجراء التحقق. |
| OnlyCheck | `1` | يمثل الوضع الذي يتم فيه إجراء التحقق، لكن نتيجته لا تؤثر على التحقق من التوقيع الرقمي. يمكنك فحص نتيجة التحقق بنفسك. |
| Strict | `2` | يمثل الوضع الذي يتم فيه إجراء التحقق وتؤثر نتيجته على التحقق من التوقيع الرقمي. إذا لم يمكن التحقق من الشهادة، فسيُعتبر التوقيع الرقمي غير صالح. يمكنك فحص نتيجة التحقق بنفسك. |

### انظر أيضًا

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


