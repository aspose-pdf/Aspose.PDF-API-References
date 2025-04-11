---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.SignaturesCoverage enum. يمثل التعداد لمستوى التغطية المقدمة من التوقيعات الرقمية في مستند
type: docs
weight: 10110
url: /ar/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enumeration

يمثل التعداد لمستوى التغطية المقدمة من التوقيعات الرقمية في مستند.

```csharp
public enum SignaturesCoverage
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Undefined | `0` | يشير إلى أن حالة تغطية التوقيعات الرقمية في المستند غير محددة. يتم استخدام هذه القيمة عادةً عندما تكون واحدة أو أكثر من التوقيعات في المستند معرضة للخطر أو لا يمكن التحقق منها، مما يمنع التقييم النهائي لتغطية التوقيع في المستند. |
| EntirelySigned | `1` | يشير إلى أن المستند مغطى بالكامل بالتوقيعات الرقمية. تشير هذه القيمة إلى أن جميع الأجزاء المطلوبة من المستند قد تم توقيعها ولا توجد توقيعات معرضة للخطر. |
| PartiallySigned | `2` | يشير إلى أن المستند موقع جزئيًا، مما يعني أن بعض، ولكن ليس كل، محتوياته مغطاة بالتوقيعات الرقمية. يتم استخدام هذه القيمة عندما تظل بعض أجزاء المستند غير موقعة أو مستبعدة من تغطية التوقيع. |

### See Also

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)