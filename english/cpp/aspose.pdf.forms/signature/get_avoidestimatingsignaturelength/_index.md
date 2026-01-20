---
title: Aspose::Pdf::Forms::Signature::get_AvoidEstimatingSignatureLength method
linktitle: get_AvoidEstimatingSignatureLength
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Signature::get_AvoidEstimatingSignatureLength method. Gets and sets an option means whether to avoid estimating the length of a signature in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.forms/signature/get_avoidestimatingsignaturelength/
---
## Signature::get_AvoidEstimatingSignatureLength method


Gets and sets an option means whether to avoid estimating the length of a signature.

```cpp
bool Aspose::Pdf::Forms::Signature::get_AvoidEstimatingSignatureLength() const
```

## Remarks


Avoids to estimate signature length before a signing document. Used for signing via [CustomSignHash](../) an via [ExternalSignature](../../externalsignature/). If [CustomSignHash](../) returns a signature longer than [DefaultSignatureLength](../), then [Aspose::Pdf::Security::SignatureLengthMismatchException](../../../aspose.pdf.security/signaturelengthmismatchexception/) will be thrown. The default value is **false**. 
## See Also

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
