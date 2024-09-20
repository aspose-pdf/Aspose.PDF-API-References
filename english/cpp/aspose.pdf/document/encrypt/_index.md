---
title: Aspose::Pdf::Document::Encrypt method
linktitle: Encrypt
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::Encrypt method. Encrypts the document. Call then Save to get encrypted version of the document in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf/document/encrypt/
---
## Document::Encrypt(System::String, System::String, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm) method


Encrypts the document. Call then Save to get encrypted version of the document.

```cpp
void Aspose::Pdf::Document::Encrypt(System::String userPassword, System::String ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| permissions | Aspose::Pdf::Permissions | [Document](../) permissions, see [Permissions](../../permissions/) for details. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Cryptographic algorithm, see [CryptoAlgorithm](../../cryptoalgorithm/) for details. |

## See Also

* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(System::String, System::String, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, bool) method


Encrypts the document. Call then Save to get encrypted version of the document.

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

## See Also

* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(System::String, System::String, System::SharedPtr\<Facades::DocumentPrivilege\>, Aspose::Pdf::CryptoAlgorithm, bool) method


Encrypts the document. Call then Save to get encrypted version of the document.

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

## See Also

* Class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
