---
title: "ValidationOptions.CheckCertificateChain"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية ValidationOptions. تحصل أو تعيين قيمة تشير إلى ما إذا كان يجب فحص سلسلة الشهادات أثناء عملية التحقق"
type: docs
weight: 20
url: /ar/net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان ينبغي فحص سلسلة الشهادات أثناء عملية التحقق.

```csharp
public bool CheckCertificateChain { get; set; }
```

## ملاحظات

عند تعيين الخاصية، سيتم فحص وجود سلسلة من الشهادات، إذا كانت غير موجودة، فإن نتيجة التحقق ستكون Undefined، وهو ما يتوافق مع سلوك Adobe Acrobat. إذا كنت تريد فقط فحص حالة الإلغاء عبر الإنترنت، فقم بتعيين الحقل إلى `false`. القيمة الافتراضية هي `false`.

### انظر أيضًا

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


