---
title: Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength method
linktitle: set_AvoidEstimatingSignatureLength
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength method. Gets and sets an option means whether to avoid estimating the length of a signature in C++.'
type: docs
weight: 1800
url: /cpp/aspose.pdf.forms/signature/set_avoidestimatingsignaturelength/
---
## Signature::set_AvoidEstimatingSignatureLength method


Gets and sets an option means whether to avoid estimating the length of a signature.

```cpp
void Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength(bool value)
```

## Remarks


Avoids to estimate signature length before a signing document. Used for signing via [CustomSignHash](../) an via [ExternalSignature](../../externalsignature/). If [CustomSignHash](../) returns a signature longer than [DefaultSignatureLength](../), then [Aspose::Pdf::Security::SignatureLengthMismatchException](../../../aspose.pdf.security/signaturelengthmismatchexception/) will be thrown. The default value is **false**. 
## See Also

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
