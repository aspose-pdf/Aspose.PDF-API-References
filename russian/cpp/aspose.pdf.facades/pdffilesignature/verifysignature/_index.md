---
title: "Aspose::Pdf::Facades::PdfFileSignature::VerifySignature метод"
linktitle: "VerifySignature"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfFileSignature::VerifySignature. Проверяет действительность подписи в C++."
type: docs
weight: 3900
url: /ru/cpp/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&) method


Проверяет действительность подписи.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |

### ReturnValue

Возвратить результат типа bool.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Проверяет действительность подписи.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |
| опции | const System::SharedPtr\<Security::ValidationOptions\>\& | Параметры проверки. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Результат проверки сертификата. |

### ReturnValue

Возвратить результат типа bool.
## Примечания



Этот метод позволяет проверить сертификат подписи с помощью OCSP и/или CRL (списка отзыва сертификатов) на предмет отзыва. Метод не проверяет цепочку сертификатов и её действительность, но проверяет, был ли отозван конечный сертификат.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) method


Проверяет действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Сертификат открытого ключа для проверки. |

### ReturnValue

Возвратить результат типа bool.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Проверяет действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Сертификат открытого ключа для проверки. |
| опции | const System::SharedPtr\<Security::ValidationOptions\>\& | Параметры проверки. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Результат проверки сертификата. |

### ReturnValue

Возвратить результат типа bool.
## Примечания



Этот метод позволяет проверить сертификат подписи с помощью OCSP и/или CRL (списка отзыва сертификатов) на предмет отзыва. Метод не проверяет цепочку сертификатов и её действительность, но проверяет, был ли отозван конечный сертификат.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::String\&) method


Проверяет действительность подписи.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::String &signName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::String\& | Имя подписи. |

### ReturnValue

Возвратить результат типа bool.

## Deprecated
Используйте метод VerifySignature(SignatureName) вместо него.

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::String\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Проверяет действительность подписи.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::String &signName, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::String\& | Имя подписи. |
| опции | const System::SharedPtr\<Security::ValidationOptions\>\& | Параметры проверки. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Результат проверки сертификата. |

### ReturnValue

Возвратить результат типа bool.
## Примечания


## Deprecated
Используйте метод VerifySignature(SignatureName, ValidationOptions, out ValidationResult) вместо него.


Этот метод позволяет проверить сертификат подписи с помощью OCSP и/или CRL (списка отзыва сертификатов) на предмет отзыва. Метод не проверяет цепочку сертификатов и её действительность, но проверяет, был ли отозван конечный сертификат.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
