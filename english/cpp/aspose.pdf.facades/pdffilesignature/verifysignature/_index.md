---
title: Aspose::Pdf::Facades::PdfFileSignature::VerifySignature method
linktitle: VerifySignature
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature::VerifySignature method. Checks the validity of a signature in C++.'
type: docs
weight: 3500
url: /cpp/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## PdfFileSignature::VerifySignature(System::String) method


Checks the validity of a signature.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(System::String signName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::String | The name of signature. |

### ReturnValue

Return a result of bool type.

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(System::String, System::SharedPtr\<Aspose::Pdf::Security::ValidationOptions\>, System::SharedPtr\<Aspose::Pdf::Security::ValidationResult\>\&) method


Checks the validity of a signature.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(System::String signName, System::SharedPtr<Aspose::Pdf::Security::ValidationOptions> options, System::SharedPtr<Aspose::Pdf::Security::ValidationResult> &validationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::String | The name of signature. |
| options | System::SharedPtr\<Aspose::Pdf::Security::ValidationOptions\> | The verification options. |
| validationResult | System::SharedPtr\<Aspose::Pdf::Security::ValidationResult\>\& | The certificate validation result. |

### ReturnValue

Return a result of bool type.
## Remarks



This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked. 
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
