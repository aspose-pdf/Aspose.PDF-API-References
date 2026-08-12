---
title: "Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions constructor"
linktitle: "CertificateEncryptionOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions constructor. Crea una instancia de la clase CertificateEncryptionOptions en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions::CertificateEncryptionOptions(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::String\&, const System::String\&) constructor


Crea una instancia de la clase [CertificateEncryptionOptions](../).

```cpp
Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicCertificate, const System::String &pfxPath, const System::String &pfxPassword)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | El certificado público. |
| pfxPath | const System::String\& | La ruta del archivo p12. |
| pfxPassword | const System::String\& | La contraseña del archivo p12. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [String](../../../system/string/)
* Class [CertificateEncryptionOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## CertificateEncryptionOptions::CertificateEncryptionOptions(const System::String\&, const System::String\&, const System::String\&) constructor


Crea una instancia de la clase [CertificateEncryptionOptions](../).

```cpp
Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions(const System::String &publicCertificatePath, const System::String &pfxPath, const System::String &pfxPassword)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicCertificatePath | const System::String\& | La ruta del archivo del certificado público. |
| pfxPath | const System::String\& | La ruta del archivo p12. |
| pfxPassword | const System::String\& | La contraseña del archivo p12. |

## Ver también

* Class [String](../../../system/string/)
* Class [CertificateEncryptionOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
