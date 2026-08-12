---
title: "Aspose::Pdf::Forms::Signature::get_AvoidEstimatingSignatureLength metod"
linktitle: "get_AvoidEstimatingSignatureLength"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::Signature::get_AvoidEstimatingSignatureLength metod. Hämtar och sätter ett alternativ som anger om man ska undvika att uppskatta längden på en signatur i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.forms/signature/get_avoidestimatingsignaturelength/
---
## Signature::get_AvoidEstimatingSignatureLength method


Hämtar och anger ett alternativ som betyder om man ska undvika att uppskatta längden på en signatur.

```cpp
bool Aspose::Pdf::Forms::Signature::get_AvoidEstimatingSignatureLength() const
```

## Anmärkningar


Undviker att uppskatta signaturens längd innan ett signeringsdokument. Används för signering via [CustomSignHash](../) och via [ExternalSignature](../../externalsignature/). Om [CustomSignHash](../) returnerar en signatur som är längre än [DefaultSignatureLength](../), kastas [Aspose::Pdf::Security::SignatureLengthMismatchException](../../../aspose.pdf.security/signaturelengthmismatchexception/). Standardvärdet är **false**.
## Se även

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
