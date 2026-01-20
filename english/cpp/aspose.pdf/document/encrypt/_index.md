---
title: Aspose::Pdf::Document::Encrypt method
linktitle: Encrypt
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::Encrypt method. Encrypts the document in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf/document/encrypt/
---
## Document::Encrypt(Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>) method


Encrypts the document.

```cpp
void Aspose::Pdf::Document::Encrypt(Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2>>> publicCertificates)
```


| Parameter | Type | Description |
| --- | --- | --- |
| permissions | Aspose::Pdf::Permissions | [Document](../) permissions, see [Permissions](../../permissions/) for details. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Cryptographic algorithm, see [CryptoAlgorithm](../../cryptoalgorithm/) for details. |
| publicCertificates | System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\> | The public certificates used for encryption — one per recipient. |
## Remarks



This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.
## See Also

* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(System::String, System::String, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm) method


Encrypts the document.

```cpp
void Aspose::Pdf::Document::Encrypt(System::String userPassword, System::String ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| permissions | Aspose::Pdf::Permissions | [Document](../) permissions, see [Permissions](../../permissions/) for details. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Cryptographic algorithm, see [CryptoAlgorithm](../../cryptoalgorithm/) for details. |
## Remarks



This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.
## See Also

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(System::String, System::String, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, bool) method


Encrypts the document.

```cpp
void Aspose::Pdf::Document::Encrypt(System::String userPassword, System::String ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| permissions | Aspose::Pdf::Permissions | [Document](../) permissions, see [Permissions](../../permissions/) for details. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Cryptographic algorithm, see [CryptoAlgorithm](../../cryptoalgorithm/) for details. |
| usePdf20 | bool | Support for revision 6 (Extension 8). |
## Remarks



This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.
## See Also

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(System::String, System::String, Aspose::Pdf::Permissions, System::SharedPtr\<Security::ICustomSecurityHandler\>) method


Encrypts the document.

```cpp
void Aspose::Pdf::Document::Encrypt(System::String userPassword, System::String ownerPassword, Aspose::Pdf::Permissions permissions, System::SharedPtr<Security::ICustomSecurityHandler> customHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| permissions | Aspose::Pdf::Permissions | [Document](../) permissions, see [Permissions](../../permissions/) for details. |
| customHandler | System::SharedPtr\<Security::ICustomSecurityHandler\> | The custom security handler. |
## Remarks



This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.
## See Also

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(System::String, System::String, System::SharedPtr\<Facades::DocumentPrivilege\>, Aspose::Pdf::CryptoAlgorithm, bool) method


Encrypts the document.

```cpp
void Aspose::Pdf::Document::Encrypt(System::String userPassword, System::String ownerPassword, System::SharedPtr<Facades::DocumentPrivilege> privileges, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| privileges | System::SharedPtr\<Facades::DocumentPrivilege\> | [Document](../) permissions, see [Permissions](../../permissions/) for details. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Cryptographic algorithm, see [CryptoAlgorithm](../../cryptoalgorithm/) for details. |
| usePdf20 | bool | Support for revision 6 (Extension 8). |
## Remarks



This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(System::String, System::String, System::SharedPtr\<Facades::DocumentPrivilege\>, System::SharedPtr\<Security::ICustomSecurityHandler\>) method


Encrypts the document.

```cpp
void Aspose::Pdf::Document::Encrypt(System::String userPassword, System::String ownerPassword, System::SharedPtr<Facades::DocumentPrivilege> privileges, System::SharedPtr<Security::ICustomSecurityHandler> customHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| privileges | System::SharedPtr\<Facades::DocumentPrivilege\> | [Document](../) permissions, see [Permissions](../../permissions/) for details. |
| customHandler | System::SharedPtr\<Security::ICustomSecurityHandler\> | The custom security handler. |
## Remarks



This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.
## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
