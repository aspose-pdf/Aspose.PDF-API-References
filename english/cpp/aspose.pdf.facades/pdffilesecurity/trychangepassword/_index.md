---
title: Aspose::Pdf::Facades::PdfFileSecurity::TryChangePassword method
linktitle: TryChangePassword
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSecurity::TryChangePassword method. Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced Does not throw an exception if process failed. with a random string if the new owner password is null or empty in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## PdfFileSecurity::TryChangePassword(System::String, System::String, System::String) method


Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced Does not throw an exception if process failed. with a random string if the new owner password is null or empty.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TryChangePassword(System::String ownerPassword, System::String newUserPassword, System::String newOwnerPassword)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | System::String | Original Owner password. |
| newUserPassword | System::String | New User password. |
| newOwnerPassword | System::String | New Owner password. |

### ReturnValue

True for success,or false.

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::TryChangePassword(System::String, System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize) method


Changes the user password and password by owner password, allows to reset [Pdf](../../../aspose.pdf/) documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Does not throw an exception if process failed.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TryChangePassword(System::String ownerPassword, System::String newUserPassword, System::String newOwnerPassword, System::SharedPtr<DocumentPrivilege> privilege, KeySize keySize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | System::String | Original owner password. |
| newUserPassword | System::String | New User password. |
| newOwnerPassword | System::String | New Owner password. |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Reset security. |
| keySize | KeySize | [KeySize.x40](../../keysize/) for 40 bits encryption, [KeySize.x128](../../keysize/) for 128 bits encryption and [KeySize.x256](../../keysize/) for 256 bits encryption. |

### ReturnValue

True for success, or false.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::TryChangePassword(System::String, System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize, Algorithm) method


Changes the user password and password by owner password, allows to reset [Pdf](../../../aspose.pdf/) documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of [KeySize](../../keysize/) and [Algorithm](../../algorithm/) values. However ([KeySize.x40](../../keysize/), [Algorithm.AES](../../algorithm/)) and ([KeySize.x256](../../keysize/), [Algorithm.RC4](../../algorithm/)) are invalid and corresponding exception will be raised if kit encounters this combination. Does not throw an exception if process failed.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TryChangePassword(System::String ownerPassword, System::String newUserPassword, System::String newOwnerPassword, System::SharedPtr<DocumentPrivilege> privilege, KeySize keySize, Algorithm cipher)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | System::String | Original owner password. |
| newUserPassword | System::String | New User password. |
| newOwnerPassword | System::String | New Owner password. |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Reset security. |
| keySize | KeySize | [KeySize.x40](../../keysize/) for 40 bits encryption, [KeySize.x128](../../keysize/) for 128 bits encryption and [KeySize.x256](../../keysize/) for 256 bits encryption. |
| cipher | Algorithm | [Algorithm.AES](../../algorithm/) to encrypt using AES algorithm or [Algorithm.RC4](../../algorithm/) for RC4 encryption. |

### ReturnValue

True for success, or false.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Enum [Algorithm](../../algorithm/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
