---
title: Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege method
linktitle: SetPrivilege
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege method. Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## PdfFileSecurity::SetPrivilege(System::SharedPtr\<DocumentPrivilege\>) method


Sets [Pdf](../../../aspose.pdf/) file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege(System::SharedPtr<DocumentPrivilege> privilege)
```


| Parameter | Type | Description |
| --- | --- | --- |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Set privilege. |

### ReturnValue

True for success.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::SetPrivilege(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>) method


Sets [Pdf](../../../aspose.pdf/) file security with original password. Throws an exception if process failed.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege(System::String userPassword, System::String ownerPassword, System::SharedPtr<DocumentPrivilege> privilege)
```


| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | System::String | Original user password. |
| ownerPassword | System::String | Original owner password. |
| privilege | System::SharedPtr\<DocumentPrivilege\> | Set privilege. |

### ReturnValue

True for success.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
