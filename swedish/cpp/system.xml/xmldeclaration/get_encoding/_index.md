---
title: "System::Xml::XmlDeclaration::get_Encoding metod"
linktitle: "get_Encoding"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDeclaration::get_Encoding metod. Returnerar kodningsnivån för XML‑dokumentet i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding method


Returnerar kodningsnivån för XML-dokumentet.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```


### ReturnValue

Det giltiga teckenkodningsnamnet.
## Anmärkningar



De mest vanligt stödda teckenkodningsnamnen för XML är följande: |||
|-|-|
| Kategori | Kodningsnamn |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (där "n" är en siffra från 1 till 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Detta värde är valfritt. Om ett värde inte är angivet, returnerar den här metoden [String::Empty](../../../system/string/empty/). Om ett kodningsattribut inte inkluderas, antas UTF-8-kodning när dokumentet skrivs eller sparas.
## Se även

* Class [String](../../../system/string/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
