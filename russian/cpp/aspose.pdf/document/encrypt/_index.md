---
title: "Метод Aspose::Pdf::Document::Encrypt"
linktitle: "Шифровать"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Document::Encrypt. Шифрует документ в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf/document/encrypt/
---
## Document::Encrypt(Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>\&) method


Шифрует документ.

```cpp
void Aspose::Pdf::Document::Encrypt(Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, const System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2>>> &publicCertificates)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| permissions | Aspose::Pdf::Permissions | [Document](../) разрешения, см. [Permissions](../../permissions/) для подробностей. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Криптографический алгоритм, см. [CryptoAlgorithm](../../cryptoalgorithm/) для подробностей. |
| publicCertificates | const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>\& | Публичные сертификаты, используемые для шифрования — по одному на получателя. |
## Примечания



Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.
## См. также

* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm) method


Шифрует документ.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | const System::String\& | Пароль пользователя. |
| ownerPassword | const System::String\& | Пароль владельца. |
| permissions | Aspose::Pdf::Permissions | [Document](../) разрешения, см. [Permissions](../../permissions/) для подробностей. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Криптографический алгоритм, см. [CryptoAlgorithm](../../cryptoalgorithm/) для подробностей. |
## Примечания



Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.
## См. также

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, bool) method


Шифрует документ.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | const System::String\& | Пароль пользователя. |
| ownerPassword | const System::String\& | Пароль владельца. |
| permissions | Aspose::Pdf::Permissions | [Document](../) разрешения, см. [Permissions](../../permissions/) для подробностей. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Криптографический алгоритм, см. [CryptoAlgorithm](../../cryptoalgorithm/) для подробностей. |
| usePdf20 | bool | Поддержка ревизии 6 (расширение 8). |
## Примечания



Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.
## См. также

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) method


Шифрует документ.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, Aspose::Pdf::Permissions permissions, const System::SharedPtr<Security::ICustomSecurityHandler> &customHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | const System::String\& | Пароль пользователя. |
| ownerPassword | const System::String\& | Пароль владельца. |
| permissions | Aspose::Pdf::Permissions | [Document](../) разрешения, см. [Permissions](../../permissions/) для подробностей. |
| customHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Пользовательский обработчик безопасности. |
## Примечания



Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.
## См. также

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, Aspose::Pdf::CryptoAlgorithm, bool) method


Шифрует документ.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<Facades::DocumentPrivilege> &privileges, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | const System::String\& | Пароль пользователя. |
| ownerPassword | const System::String\& | Пароль владельца. |
| privileges | const System::SharedPtr\<Facades::DocumentPrivilege\>\& | [Document](../) разрешения, см. [Permissions](../../permissions/) для подробностей. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Криптографический алгоритм, см. [CryptoAlgorithm](../../cryptoalgorithm/) для подробностей. |
| usePdf20 | bool | Поддержка ревизии 6 (расширение 8). |
## Примечания



Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) method


Шифрует документ.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<Facades::DocumentPrivilege> &privileges, const System::SharedPtr<Security::ICustomSecurityHandler> &customHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | const System::String\& | Пароль пользователя. |
| ownerPassword | const System::String\& | Пароль владельца. |
| privileges | const System::SharedPtr\<Facades::DocumentPrivilege\>\& | [Document](../) разрешения, см. [Permissions](../../permissions/) для подробностей. |
| customHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Пользовательский обработчик безопасности. |
## Примечания



Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
