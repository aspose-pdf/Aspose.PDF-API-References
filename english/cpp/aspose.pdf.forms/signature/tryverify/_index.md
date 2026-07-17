---
title: Aspose::Pdf::Forms::Signature::TryVerify method
linktitle: TryVerify
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Signature::TryVerify method. Try to verify the document regarding this signature and return true if document is valid or otherwise false in C++.'
type: docs
weight: 3000
url: /cpp/aspose.pdf.forms/signature/tryverify/
---
## Signature::TryVerify(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Try to verify the document regarding this signature and return true if document is valid or otherwise false.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | The verification options. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | The certificate validation result. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | The verification result. |

### ReturnValue

Returns true if the signature was processed correctly. Returns false if an error occurred during the verification process or the signature was corrupted or compromised.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::TryVerify(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Try to verify the document regarding this signature and return true if document is valid or otherwise false. Verification is performed using the external public key certificate.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | The public key certificate for verification. |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | The verification options. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | The certificate validation result. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | The verification result. |

### ReturnValue

Returns true if the signature was processed correctly. Returns false if an error occurred during the verification process or the signature was corrupted or compromised.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::TryVerify(System::SharedPtr\<Security::VerificationResult\>\&) method


Try to verify the document regarding this signature and return true if document is valid or otherwise false.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | The verification result. |

### ReturnValue

Returns true if the signature was processed correctly. Returns false if an error occurred during the verification process or the signature was corrupted or compromised.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
