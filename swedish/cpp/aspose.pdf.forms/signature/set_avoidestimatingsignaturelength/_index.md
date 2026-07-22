---
title: "Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength‑metod"
linktitle: "set_AvoidEstimatingSignatureLength"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength‑metod. Hämtar och anger ett alternativ som bestämmer om uppskattning av signaturens längd ska undvikas i C++."
type: docs
weight: 1800
url: /sv/cpp/aspose.pdf.forms/signature/set_avoidestimatingsignaturelength/
---
## Signature::set_AvoidEstimatingSignatureLength method


Hämtar och anger ett alternativ som betyder om man ska undvika att uppskatta längden på en signatur.

```cpp
void Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength(bool value)
```

## Anmärkningar


Undviker att uppskatta signaturens längd innan ett signeringsdokument. Används för signering via [CustomSignHash](../) och via [ExternalSignature](../../externalsignature/). Om [CustomSignHash](../) returnerar en signatur som är längre än [DefaultSignatureLength](../), kastas [Aspose::Pdf::Security::SignatureLengthMismatchException](../../../aspose.pdf.security/signaturelengthmismatchexception/). Standardvärdet är **false**.
## Se även

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
