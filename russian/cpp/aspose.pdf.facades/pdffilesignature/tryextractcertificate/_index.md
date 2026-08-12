---
title: "Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate метод"
linktitle: "TryExtractCertificate"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate метод. Извлекает единственный сертификат X.509 подписи'' в виде потока в C++."
type: docs
weight: 3700
url: /ru/cpp/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## PdfFileSignature::TryExtractCertificate(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::IO::Stream\>\&) method


Извлекает единственный сертификат X.509 подписи в виде потока.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate(const System::SharedPtr<SignatureName> &signName, System::SharedPtr<System::IO::Stream> &stream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |
| поток | System::SharedPtr\<System::IO::Stream\>\& | Если сертификат найден, возвращает поток единственного сертификата X.509; в противном случае — null. |

### ReturnValue

Найден действительный сертификат.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryExtractCertificate(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) method


Извлекает единственный сертификат X.509 подписи.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate(const System::SharedPtr<SignatureName> &signName, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |
| сертификат | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Если сертификат найден, возвращает объект единственного сертификата X.509; в противном случае — null. |

### ReturnValue

Найден действительный сертификат.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
