---
title: "Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege metod"
linktitle: "SetPrivilege"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege metod. Ställer in Pdf-filens säkerhet med tomma användar-/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas i C++."
type: docs
weight: 1400
url: /sv/cpp/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## PdfFileSecurity::SetPrivilege(const System::SharedPtr\<DocumentPrivilege\>\&) method


Ställer in [Pdf](../../../aspose.pdf/) filens säkerhet med tomma användar-/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege(const System::SharedPtr<DocumentPrivilege> &privilege)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| privileg | const System::SharedPtr\<DocumentPrivilege\>\& | Ställ in privileg. |

### ReturnValue

Sant för framgång.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::SetPrivilege(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&) method


Ställer in [Pdf](../../../aspose.pdf/) filsäkerhet med originalt lösenord. Kastar ett undantag om processen misslyckas.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | const System::String\& | Originalt användarlösenord. |
| ownerPassword | const System::String\& | Originalt ägarlösenord. |
| privileg | const System::SharedPtr\<DocumentPrivilege\>\& | Ställ in privileg. |

### ReturnValue

Sant för framgång.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
