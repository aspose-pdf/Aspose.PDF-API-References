---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: خاصية التوقيع. تحصل وتضبط خيار يعني ما إذا كان يجب تجنب تقدير طول التوقيع
type: docs
weight: 30
url: /ar/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## خاصية Signature.AvoidEstimatingSignatureLength

تحصل وتضبط خيار يعني ما إذا كان يجب تجنب تقدير طول التوقيع.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## ملاحظات

تتجنب تقدير طول التوقيع قبل توقيع المستند. تُستخدم للتوقيع عبر [`CustomSignHash`](../customsignhash/) وعبر [`ExternalSignature`](../../externalsignature/). إذا أعاد [`CustomSignHash`](../customsignhash/) توقيعًا أطول من [`DefaultSignatureLength`](../defaultsignaturelength/)، فسيتم طرح [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/). القيمة الافتراضية هي `false`.

### انظر أيضًا

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)