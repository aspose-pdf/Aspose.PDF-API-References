---
title: Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature method
linktitle: TryVerifySignature
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature method. Try to check the validity of a signature in C++.'
type: docs
weight: 3800
url: /cpp/aspose.pdf.facades/pdffilesignature/tryverifysignature/
---
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Try to check the validity of a signature.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | The name of signature. |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | The verification options. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | The certificate validation result. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | The verification result. |

### ReturnValue

Returns **true** if the signature was processed correctly. Returns **false** if an error occurred during the verification process or the signature was corrupted or compromised.
## Remarks



This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Try to check the validity of a signature. Verification is performed using the external public key certificate.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | The name of signature. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | The public key certificate for verification. |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | The verification options. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | The certificate validation result. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | The result of verification. |

### ReturnValue

Returns **true** if the signature was processed correctly. Returns **false** if an error occurred during the verification process or the signature was corrupted or compromised.
## Remarks



This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Try to check the validity of a signature. Verification is performed using the external public key certificate.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | The name of signature. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | The public key certificate for verification. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | The result of verification. |

### ReturnValue

Returns **true** if the signature was processed correctly. Returns **false** if an error occurred during the verification process or the signature was corrupted or compromised.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Try to check the validity of a signature.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | The name of signature. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | The result of verification. |

### ReturnValue

Returns **true** if the signature was processed correctly. Returns **false** if an error occurred during the verification process or the signature was corrupted or compromised.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
