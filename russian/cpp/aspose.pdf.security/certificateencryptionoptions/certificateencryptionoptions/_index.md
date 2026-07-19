---
title: "Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions constructor"
linktitle: "CertificateEncryptionOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions constructor. Создаёт экземпляр класса CertificateEncryptionOptions в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions::CertificateEncryptionOptions(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::String\&, const System::String\&) constructor


Создает экземпляр класса [CertificateEncryptionOptions](../).

```cpp
Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicCertificate, const System::String &pfxPath, const System::String &pfxPassword)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| publicCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Публичный сертификат. |
| pfxPath | const System::String\& | Путь к файлу архива p12. |
| pfxPassword | const System::String\& | Пароль к файлу архива p12. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [String](../../../system/string/)
* Class [CertificateEncryptionOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
## CertificateEncryptionOptions::CertificateEncryptionOptions(const System::String\&, const System::String\&, const System::String\&) constructor


Создает экземпляр класса [CertificateEncryptionOptions](../).

```cpp
Aspose::Pdf::Security::CertificateEncryptionOptions::CertificateEncryptionOptions(const System::String &publicCertificatePath, const System::String &pfxPath, const System::String &pfxPassword)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| publicCertificatePath | const System::String\& | Путь к файлу публичного сертификата. |
| pfxPath | const System::String\& | Путь к файлу архива p12. |
| pfxPassword | const System::String\& | Пароль к файлу архива p12. |

## См. также

* Class [String](../../../system/string/)
* Class [CertificateEncryptionOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
