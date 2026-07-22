---
title: "Aspose::Pdf::Facades::PdfFileSecurity::ChangePassword metod"
linktitle: "ChangePassword"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSecurity::ChangePassword metod. Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## PdfFileSecurity::ChangePassword(const System::String\&, const System::String\&, const System::String\&) method


Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::ChangePassword(const System::String &ownerPassword, const System::String &newUserPassword, const System::String &newOwnerPassword)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | const System::String\& | Originalt ägarlösenord. |
| newUserPassword | const System::String\& | Nytt användarlösenord. |
| newOwnerPassword | const System::String\& | Nytt ägarlösenord. |

### ReturnValue

Sant för framgång.

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::ChangePassword(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) method


Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av [Pdf](../../../aspose.pdf/) dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::ChangePassword(const System::String &ownerPassword, const System::String &newUserPassword, const System::String &newOwnerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | const System::String\& | Originalt ägarlösenord. |
| newUserPassword | const System::String\& | Nytt användarlösenord. |
| newOwnerPassword | const System::String\& | Nytt ägarlösenord. |
| privileg | const System::SharedPtr\<DocumentPrivilege\>\& | Återställ säkerhet. |
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
## PdfFileSecurity::ChangePassword(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) method


Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av [Pdf](../../../aspose.pdf/) dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av [KeySize](../../keysize/) och [Algorithm](../../algorithm/) värden. Dock är ([KeySize.x40](../../keysize/), [Algorithm.AES](../../algorithm/)) och ([KeySize.x256](../../keysize/), [Algorithm.RC4](../../algorithm/)) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar ett undantag om processen misslyckas.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::ChangePassword(const System::String &ownerPassword, const System::String &newUserPassword, const System::String &newOwnerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize, Algorithm cipher)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | const System::String\& | Originalt ägarlösenord. |
| newUserPassword | const System::String\& | Nytt användarlösenord. |
| newOwnerPassword | const System::String\& | Nytt ägarlösenord. |
| privileg | const System::SharedPtr\<DocumentPrivilege\>\& | Återställ säkerhet. |
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
