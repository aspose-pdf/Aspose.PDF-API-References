---
title: Aspose::Pdf::Forms::ExternalSignature::ExternalSignature constructor
linktitle: ExternalSignature
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::ExternalSignature::ExternalSignature constructor. Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature::ExternalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) constructor


Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| certificate | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\> | The certificate with the private key. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>, bool) constructor


Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate, bool detached)
```


| Parameter | Type | Description |
| --- | --- | --- |
| certificate | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\> | The certificate with the private key. |
| detached | bool | True if the signature should be detached, otherwise false. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(System::String, bool) constructor


Creates a PKCS#7 (detached) signature using a X509Certificate2 as base64 string.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(System::String base64, bool detached)
```


| Parameter | Type | Description |
| --- | --- | --- |
| base64 | System::String | X509Certificate2 as base64 string. |
| detached | bool | True if the signature should be detached, otherwise false. |

## See Also

* Class [String](../../../system/string/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
