---
title: "Aspose::Pdf::Facades::PdfFileSecurity::TrySetPrivilege method"
linktitle: "TrySetPrivilege"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSecurity::TrySetPrivilege method. Ställer in Pdf‑filens säkerhet med originallösenordet. Kastar inte ett undantag om processen misslyckas i C++."
type: docs
weight: 1800
url: /sv/cpp/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity::TrySetPrivilege method


Ställer in [Pdf](../../../aspose.pdf/)-filens säkerhet med originallösenordet. Kastar inte ett undantag om processen misslyckas.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TrySetPrivilege(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | const System::String\& | Originalt användarlösenord. |
| ownerPassword | const System::String\& | Originalt ägarlösenord. |
| privileg | const System::SharedPtr\<DocumentPrivilege\>\& | Ställ in privileg. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
