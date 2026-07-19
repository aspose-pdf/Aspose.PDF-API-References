---
title: "Метод Aspose::Pdf::Forms::Signature::Verify"
linktitle: "Verify"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Forms::Signature::Verify. Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false в C++."
type: docs
weight: 3100
url: /ru/cpp/aspose.pdf.forms/signature/verify/
---
## Signature::Verify() method


Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify()
```


### ReturnValue

true, если документ действителен.

## См. также

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::Verify(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify(const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| опции | const System::SharedPtr\<Security::ValidationOptions\>\& | Параметры проверки. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Результат проверки сертификата. |

### ReturnValue

true, если документ действителен.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::Verify(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. Проверка выполняется с использованием внешнего сертификата открытого ключа.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Сертификат открытого ключа для проверки. |
| опции | const System::SharedPtr\<Security::ValidationOptions\>\& | Параметры проверки. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Результат проверки сертификата. |

### ReturnValue

true, если документ действителен.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
