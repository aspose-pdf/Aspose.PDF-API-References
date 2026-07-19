---
title: "Метод Aspose::Pdf::Forms::Signature::TryVerify"
linktitle: "TryVerify"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Forms::Signature::TryVerify. Пытается проверить документ относительно этой подписи и возвращает true, если документ действителен, иначе false в C++."
type: docs
weight: 3000
url: /ru/cpp/aspose.pdf.forms/signature/tryverify/
---
## Signature::TryVerify(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Попробуйте проверить документ относительно этой подписи и вернуть true, если документ действителен, иначе false.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| опции | const System::SharedPtr\<Security::ValidationOptions\>\& | Параметры проверки. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Результат проверки сертификата. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Результат проверки. |

### ReturnValue

Возвращает true, если подпись была обработана корректно. Возвращает false, если во время процесса проверки произошла ошибка или подпись была повреждена или скомпрометирована.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::TryVerify(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Попробуйте проверить документ относительно этой подписи и вернуть true, если документ действителен, иначе false. Проверка выполняется с использованием внешнего сертификата открытого ключа.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Сертификат открытого ключа для проверки. |
| опции | const System::SharedPtr\<Security::ValidationOptions\>\& | Параметры проверки. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Результат проверки сертификата. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Результат проверки. |

### ReturnValue

Возвращает true, если подпись была обработана корректно. Возвращает false, если во время процесса проверки произошла ошибка или подпись была повреждена или скомпрометирована.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::TryVerify(System::SharedPtr\<Security::VerificationResult\>\&) method


Попробуйте проверить документ относительно этой подписи и вернуть true, если документ действителен, иначе false.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Результат проверки. |

### ReturnValue

Возвращает true, если подпись была обработана корректно. Возвращает false, если во время процесса проверки произошла ошибка или подпись была повреждена или скомпрометирована.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
