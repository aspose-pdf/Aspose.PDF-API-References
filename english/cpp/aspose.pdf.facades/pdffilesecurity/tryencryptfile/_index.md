---
title: Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile method
linktitle: TryEncryptFile
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile method. Encrypts Pdf file with userpassword and ownerpassword and sets the document''s privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Does not throw an exception if process failed in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity::TryEncryptFile method


Encrypts [Pdf](../../../aspose.pdf/) file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Does not throw an exception if process failed.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile(System::String userPassword, System::String ownerPassword, System::SharedPtr<DocumentPrivilege> privilege, KeySize keySize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | User password. |
| ownerPassword | System::String | Owner password. |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Set privilege. |
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
