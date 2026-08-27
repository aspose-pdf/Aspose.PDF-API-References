---
title: "التعداد SignaturesCoverage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "التعداد Aspose.Pdf.Signatures.SignaturesCoverage. يمثل تعدادًا لمستوى التغطية التي توفرها التوقيعات الرقمية في المستند"
type: docs
weight: 10290
url: /ar/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enumeration

يمثل تعداد لمستوى التغطية التي توفرها التوقيعات الرقمية في المستند.

```csharp
public enum SignaturesCoverage
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Undefined | `0` | يشير إلى أن حالة تغطية التوقيعات الرقمية في المستند غير معرفة. عادةً ما يُستخدم هذا القيمة عندما تكون توقيع أو أكثر في المستند معرضة للخطر أو لا يمكن التحقق منها، مما يمنع تقييمًا نهائيًا لتغطية توقيع المستند. |
| EntirelySigned | `1` | يشير إلى أن المستند مغطى بالكامل بالتوقيعات الرقمية. هذه القيمة تعني أن جميع الأجزاء المطلوبة من المستند تم توقيعها ولا توجد توقيعات معرضة للخطر. |
| PartiallySigned | `2` | يشير إلى أن المستند موقع جزئيًا، أي أن بعض محتوياته، ولكن ليس كلها، مغطاة بالتوقيعات الرقمية. تُستخدم هذه القيمة عندما تظل بعض أجزاء المستند غير موقعة أو مستثناة من تغطية التوقيع. |

### انظر أيضًا

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)


