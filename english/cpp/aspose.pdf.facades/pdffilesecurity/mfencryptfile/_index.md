---
title: Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile method
linktitle: MfEncryptFile
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile method. Encrypts Pdf file with userpassword and ownerpassword and sets the document''s privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.facades/pdffilesecurity/mfencryptfile/
---
## PdfFileSecurity::MfEncryptFile(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize) method


Encrypts [Pdf](../../../aspose.pdf/) file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile(System::String userPassword, System::String ownerPassword, System::SharedPtr<DocumentPrivilege> privilege, KeySize keySize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Set privilege. |
| keySize | KeySize | [KeySize.x40](../../keysize/) for 40 bits encryption, [KeySize.x128](../../keysize/) for 128 bits encryption and [KeySize.x256](../../keysize/) for 256 bits encryption. |

### ReturnValue

True for success.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::MfEncryptFile(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize, Algorithm) method


Encrypts [Pdf](../../../aspose.pdf/) file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. There are 6 possible combinations of [KeySize](../../keysize/) and [Algorithm](../../algorithm/) values. However ([KeySize.x40](../../keysize/), [Algorithm.AES](../../algorithm/)) and ([KeySize.x256](../../keysize/), [Algorithm.RC4](../../algorithm/)) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile(System::String userPassword, System::String ownerPassword, System::SharedPtr<DocumentPrivilege> privilege, KeySize keySize, Algorithm cipher)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Set privilege. |
| keySize | KeySize | [KeySize.x40](../../keysize/) for 40 bits encryption, [KeySize.x128](../../keysize/) for 128 bits encryption and [KeySize.x256](../../keysize/) for 256 bits encryption. |
| cipher | Algorithm | [Algorithm.AES](../../algorithm/) to encrypt using AES algorithm or [Algorithm.RC4](../../algorithm/) for RC4 encryption. |

### ReturnValue

True for success.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Enum [Algorithm](../../algorithm/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
