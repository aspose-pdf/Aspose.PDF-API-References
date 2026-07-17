---
title: Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions constructor
linktitle: CertificateEncryptionOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions constructor. Creates an instance of CertificateEncryptionOptions class in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions::CertificateEncryptionOptions(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::String\&, const System::String\&) constructor


Creates an instance of [CertificateEncryptionOptions](../) class.

```cpp
Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicCertificate, const System::String &pfxPath, const System::String &pfxPassword)
```


| Parameter | Type | Description |
| --- | --- | --- |
| publicCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | The public certificate. |
| pfxPath | const System::String\& | The p12 archive file path. |
| pfxPassword | const System::String\& | The p12 archive file password. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [String](../../../system/string/)
* Class [CertificateEncryptionOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## CertificateEncryptionOptions::CertificateEncryptionOptions(const System::String\&, const System::String\&, const System::String\&) constructor


Creates an instance of [CertificateEncryptionOptions](../) class.

```cpp
Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions(const System::String &publicCertificatePath, const System::String &pfxPath, const System::String &pfxPassword)
```


| Parameter | Type | Description |
| --- | --- | --- |
| publicCertificatePath | const System::String\& | The public certificate file path. |
| pfxPath | const System::String\& | The p12 archive file path. |
| pfxPassword | const System::String\& | The p12 archive file password. |

## See Also

* Class [String](../../../system/string/)
* Class [CertificateEncryptionOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
