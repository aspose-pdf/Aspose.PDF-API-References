---
title: "Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile method"
linktitle: "TryEncryptFile"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile method. Krypterar Pdf‑fil med användarlösenord och ägarlösenord och anger dokumentets åtkomstbehörigheter. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas i C++."
type: docs
weight: 1700
url: /sv/cpp/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity::TryEncryptFile method


Krypterar [Pdf](../../../aspose.pdf/)‑fil med användarlösenord och ägarlösenord och anger dokumentets åtkomstbehörigheter. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | const System::String\& | Användarlösenord. |
| ownerPassword | const System::String\& | Ägarlösenord. |
| privileg | const System::SharedPtr\<DocumentPrivilege\>\& | Ställ in privileg. |
| keySize | KeySize | [KeySize.x40](../../keysize/) för 40‑bits kryptering, [KeySize.x128](../../keysize/) för 128‑bits kryptering och [KeySize.x256](../../keysize/) för 256‑bits kryptering. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
