---
title: "Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature метод"
linktitle: "TryVerifySignature"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature method. Пытается проверить корректность подписи в C++."
type: docs
weight: 3800
url: /ru/cpp/aspose.pdf.facades/pdffilesignature/tryverifysignature/
---
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Попробуйте проверить действительность подписи.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |
| опции | const System::SharedPtr\<Security::ValidationOptions\>\& | Параметры проверки. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Результат проверки сертификата. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Результат проверки. |

### ReturnValue

Возвращает **true**, если подпись была обработана корректно. Возвращает **false**, если во время процесса проверки произошла ошибка или подпись была повреждена или скомпрометирована.
## Примечания



Этот метод позволяет проверить сертификат подписи с помощью OCSP и/или CRL (списка отзыва сертификатов) на предмет отзыва. Метод не проверяет цепочку сертификатов и её действительность, но проверяет, был ли отозван конечный сертификат.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Попробуйте проверить действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Сертификат открытого ключа для проверки. |
| опции | const System::SharedPtr\<Security::ValidationOptions\>\& | Параметры проверки. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Результат проверки сертификата. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Результат проверки. |

### ReturnValue

Возвращает **true**, если подпись была обработана корректно. Возвращает **false**, если во время процесса проверки произошла ошибка или подпись была повреждена или скомпрометирована.
## Примечания



Этот метод позволяет проверить сертификат подписи с помощью OCSP и/или CRL (списка отзыва сертификатов) на предмет отзыва. Метод не проверяет цепочку сертификатов и её действительность, но проверяет, был ли отозван конечный сертификат.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Попробуйте проверить действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Сертификат открытого ключа для проверки. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Результат проверки. |

### ReturnValue

Возвращает **true**, если подпись была обработана корректно. Возвращает **false**, если во время процесса проверки произошла ошибка или подпись была повреждена или скомпрометирована.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Попробуйте проверить действительность подписи.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Результат проверки. |

### ReturnValue

Возвращает **true**, если подпись была обработана корректно. Возвращает **false**, если во время процесса проверки произошла ошибка или подпись была повреждена или скомпрометирована.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
