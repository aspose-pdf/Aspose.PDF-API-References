---
title: "Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile method"
linktitle: "MfEncryptFile"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile method. Krypterar Pdf‑fil med användarlösenord och ägarlösenord och anger dokumentets åtkomstbehörigheter. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.pdf.facades/pdffilesecurity/mfencryptfile/
---
## PdfFileSecurity::MfEncryptFile(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) method


Krypterar [Pdf](../../../aspose.pdf/)‑fil med användarlösenord och ägarlösenord och anger dokumentets åtkomstbehörigheter. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | const System::String\& | Användarlösenord. |
| ownerPassword | const System::String\& | Ägarlösenord. |
| privileg | const System::SharedPtr\<DocumentPrivilege\>\& | Ställ in privileg. |
| keySize | KeySize | [KeySize.x40](../../keysize/) för 40‑bits kryptering, [KeySize.x128](../../keysize/) för 128‑bits kryptering och [KeySize.x256](../../keysize/) för 256‑bits kryptering. |

### ReturnValue

Sant för framgång.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::MfEncryptFile(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) method


Krypterar [Pdf](../../../aspose.pdf/)‑fil med användarlösenord och ägarlösenord och anger dokumentets åtkomstbehörigheter. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av [KeySize](../../keysize/) och [Algorithm](../../algorithm/)-värden. Dock är ([KeySize.x40](../../keysize/), [Algorithm.AES](../../algorithm/)) och ([KeySize.x256](../../keysize/), [Algorithm.RC4](../../algorithm/)) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar ett undantag om processen misslyckas.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize, Algorithm cipher)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | const System::String\& | Användarlösenord. |
| ownerPassword | const System::String\& | Ägarlösenord. |
| privileg | const System::SharedPtr\<DocumentPrivilege\>\& | Ställ in privileg. |
| keySize | KeySize | [KeySize.x40](../../keysize/) för 40‑bits kryptering, [KeySize.x128](../../keysize/) för 128‑bits kryptering och [KeySize.x256](../../keysize/) för 256‑bits kryptering. |
| cipher | Algorithm | [Algorithm.AES](../../algorithm/) för att kryptera med AES-algoritmen eller [Algorithm.RC4](../../algorithm/) för RC4-kryptering. |

### ReturnValue

Sant för framgång.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Enum [Algorithm](../../algorithm/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
