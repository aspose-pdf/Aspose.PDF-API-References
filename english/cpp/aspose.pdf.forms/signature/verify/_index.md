---
title: Aspose::Pdf::Forms::Signature::Verify method
linktitle: Verify
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Signature::Verify method. Verify the document regarding this signature and return true if document is valid or otherwise false in C++.'
type: docs
weight: 3000
url: /cpp/aspose.pdf.forms/signature/verify/
---
## Signature::Verify() method


Verify the document regarding this signature and return true if document is valid or otherwise false.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify()
```


### ReturnValue

true if document is valid.

## See Also

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::Verify(System::SharedPtr\<Security::ValidationOptions\>, System::SharedPtr\<Security::ValidationResult\>\&) method


Verify the document regarding this signature and return true if document is valid or otherwise false.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify(System::SharedPtr<Security::ValidationOptions> options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| options | System::SharedPtr\<Security::ValidationOptions\> | The verification options. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | The certificate validation result. |

### ReturnValue

true if document is valid.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::Verify(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>, System::SharedPtr\<Security::ValidationOptions\>, System::SharedPtr\<Security::ValidationResult\>\&) method


Verify the document regarding this signature and return true if document is valid or otherwise false. Verification is performed using the external public key certificate.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> publicKeyCertificate, System::SharedPtr<Security::ValidationOptions> options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| publicKeyCertificate | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\> | The public key certificate for verification. |
| options | System::SharedPtr\<Security::ValidationOptions\> | The verification options. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | The certificate validation result. |

### ReturnValue

true if document is valid.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
