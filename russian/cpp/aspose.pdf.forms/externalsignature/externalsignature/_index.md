---
title: "Aspose::Pdf::Forms::ExternalSignature::ExternalSignature конструктор"
linktitle: "ExternalSignature"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::ExternalSignature::ExternalSignature конструктор. Создаёт отделённую подпись PKCS#7 (detached) с использованием X509Certificate2. Поддерживает USB‑смарт‑карты, токены без экспортируемых закрытых ключей в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature::ExternalSignature(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) constructor


Создаёт отделённую подпись PKCS#7 **(detached)** с использованием X509Certificate2. Поддерживает usb‑смарткарты, токены без экспортируемых закрытых ключей.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| сертификат | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Сертификат с закрытым ключом. |
## Примечания



Алгоритм хеширования будет автоматически выбран на основе данных ключа сертификата.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, bool) constructor


Создаёт отдельную подпись PKCS#7 с использованием X509Certificate2. Поддерживает USB‑смарт‑карты, токены без экспортируемых закрытых ключей.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate, bool detached)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| сертификат | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Сертификат с закрытым ключом. |
| отделённый | bool | True, если подпись должна быть отделённой, иначе false. |
## Примечания



Если detached установлен в false, алгоритм хеширования всегда будет **SHA1**. В противном случае алгоритм хеширования будет автоматически выбран на основе данных ключа сертификата (см. [DigestHashAlgorithm::Auto](../../../aspose.pdf/digesthashalgorithm/) ).
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, DigestHashAlgorithm) constructor


Создаёт отделённую подпись PKCS#7 **(detached)** с использованием X509Certificate2. Поддерживает usb‑смарткарты, токены без экспортируемых закрытых ключей.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate, DigestHashAlgorithm digestHashAlgorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| сертификат | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Сертификат с закрытым ключом. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм хеширования для подписи документа. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::String\&, bool) constructor


Создаёт подпись PKCS#7 с использованием X509Certificate2 в виде строки base64.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::String &base64, bool detached)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| base64 | const System::String\& | X509Certificate2 в виде строки base64. |
| отделённый | bool | True, если подпись должна быть отделённой, иначе false. |
## Примечания



Если detached установлен в false, алгоритм хеширования всегда будет **SHA1**. В противном случае алгоритм хеширования будет автоматически выбран на основе данных ключа сертификата (см. [DigestHashAlgorithm::Auto](../../../aspose.pdf/digesthashalgorithm/) ).
## См. также

* Class [String](../../../system/string/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::String\&, DigestHashAlgorithm) constructor


Создаёт подпись PKCS#7 **(detached)** с использованием X509Certificate2 в виде строки base64.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::String &base64, DigestHashAlgorithm digestHashAlgorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| base64 | const System::String\& | X509Certificate2 в виде строки base64. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм хеширования для подписи документа. |

## См. также

* Class [String](../../../system/string/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
