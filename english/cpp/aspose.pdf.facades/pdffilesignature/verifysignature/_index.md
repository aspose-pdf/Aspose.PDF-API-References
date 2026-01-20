---
title: Aspose::Pdf::Facades::PdfFileSignature::VerifySignature method
linktitle: VerifySignature
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature::VerifySignature method. Checks the validity of a signature in C++.'
type: docs
weight: 3800
url: /cpp/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## PdfFileSignature::VerifySignature(System::SharedPtr\<SignatureName\>) method


Checks the validity of a signature.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(System::SharedPtr<SignatureName> signName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::SharedPtr\<SignatureName\> | The name of signature. |

### ReturnValue

Return a result of bool type.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(System::SharedPtr\<SignatureName\>, System::SharedPtr\<Security::ValidationOptions\>, System::SharedPtr\<Security::ValidationResult\>\&) method


Checks the validity of a signature.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(System::SharedPtr<SignatureName> signName, System::SharedPtr<Security::ValidationOptions> options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::SharedPtr\<SignatureName\> | The name of signature. |
| options | System::SharedPtr\<Security::ValidationOptions\> | The verification options. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | The certificate validation result. |

### ReturnValue

Return a result of bool type.
## Remarks



This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(System::SharedPtr\<SignatureName\>, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) method


Checks the validity of a signature. Verification is performed using the external public key certificate.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(System::SharedPtr<SignatureName> signName, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> publicKeyCertificate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::SharedPtr\<SignatureName\> | The name of signature. |
| publicKeyCertificate | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\> | The public key certificate for verification. |

### ReturnValue

Return a result of bool type.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(System::SharedPtr\<SignatureName\>, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>, System::SharedPtr\<Security::ValidationOptions\>, System::SharedPtr\<Security::ValidationResult\>\&) method


Checks the validity of a signature. Verification is performed using the external public key certificate.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(System::SharedPtr<SignatureName> signName, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> publicKeyCertificate, System::SharedPtr<Security::ValidationOptions> options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::SharedPtr\<SignatureName\> | The name of signature. |
| publicKeyCertificate | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\> | The public key certificate for verification. |
| options | System::SharedPtr\<Security::ValidationOptions\> | The verification options. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | The certificate validation result. |

### ReturnValue

Return a result of bool type.
## Remarks



This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
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

## Deprecated
Use VerifySignature(SignatureName) method instead. 

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(System::String, System::SharedPtr\<Security::ValidationOptions\>, System::SharedPtr\<Security::ValidationResult\>\&) method


Checks the validity of a signature.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(System::String signName, System::SharedPtr<Security::ValidationOptions> options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::String | The name of signature. |
| options | System::SharedPtr\<Security::ValidationOptions\> | The verification options. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | The certificate validation result. |

### ReturnValue

Return a result of bool type.
## Remarks


## Deprecated
Use VerifySignature(SignatureName, ValidationOptions, out ValidationResult) method instead. 


This method allows you to check the signing certificate using OCSP and/or CRL (certificate revocation list) for revocation. This method does not check the certificate chain and its validity, but it does check whether the end certificate has been revoked. 
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
