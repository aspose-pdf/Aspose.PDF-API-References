---
title: "Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate метод"
linktitle: "ExtractCertificate"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate метод. Извлекает один X.509 сертификат подписи как поток в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf.facades/pdffilesignature/extractcertificate/
---
## PdfFileSignature::ExtractCertificate(const System::SharedPtr\<SignatureName\>\&) method


Извлекает единственный сертификат X.509 подписи в виде потока.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate(const System::SharedPtr<SignatureName> &signName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |

### ReturnValue

Если сертификат найден, возвращает один X.509 сертификат; в противном случае, null.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::ExtractCertificate(const System::String\&) method


Извлекает единственный сертификат X.509 подписи в виде потока.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate(const System::String &signName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::String\& | Имя подписи. |

### ReturnValue

Если сертификат найден, возвращает одиночный сертификат X.509; в противном случае — null.

## Deprecated
Используйте метод ExtractCertificate(SignatureName) вместо этого.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
