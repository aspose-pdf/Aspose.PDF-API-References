---
title: Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions constructor
linktitle: CertificateEncryptionOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions constructor. Creates an instance of CertificateEncryptionOptions class in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions::CertificateEncryptionOptions(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>, System::String, System::String) constructor


Creates an instance of [CertificateEncryptionOptions](../) class.

```cpp
Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> publicCertificate, System::String pfxPath, System::String pfxPassword)
```


| Parameter | Type | Description |
| --- | --- | --- |
| publicCertificate | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\> | The public certificate. |
| pfxPath | System::String | The p12 archive file path. |
| pfxPassword | System::String | The p12 archive file password. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [String](../../../system/string/)
* Class [CertificateEncryptionOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## CertificateEncryptionOptions::CertificateEncryptionOptions(System::String, System::String, System::String) constructor


Creates an instance of [CertificateEncryptionOptions](../) class.

```cpp
Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions(System::String publicCertificatePath, System::String pfxPath, System::String pfxPassword)
```


| Parameter | Type | Description |
| --- | --- | --- |
| publicCertificatePath | System::String | The public certificate file path. |
| pfxPath | System::String | The p12 archive file path. |
| pfxPassword | System::String | The p12 archive file password. |

## See Also

* Class [String](../../../system/string/)
* Class [CertificateEncryptionOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
