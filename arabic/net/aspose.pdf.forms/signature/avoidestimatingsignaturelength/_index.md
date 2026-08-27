---
title: "Signature.AvoidEstimatingSignatureLength"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Signature. الحصول وتعيين خيار يعني ما إذا كان يجب تجنب تقدير طول التوقيع"
type: docs
weight: 30
url: /ar/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength property

يحصل أو يعيّن خيارًا يحدد ما إذا كان يجب تجنب تقدير طول التوقيع.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## ملاحظات

يتجنب تقدير طول التوقيع قبل وثيقة التوقيع. يُستخدم للتوقيع عبر [`CustomSignHash`](../customsignhash/) أو عبر [`ExternalSignature`](../../externalsignature/). إذا أعاد [`CustomSignHash`](../customsignhash/) توقيعًا أطول من [`DefaultSignatureLength`](../defaultsignaturelength/)، فسيتم رمي [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/). القيمة الافتراضية هي `false`.

### انظر أيضًا

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


