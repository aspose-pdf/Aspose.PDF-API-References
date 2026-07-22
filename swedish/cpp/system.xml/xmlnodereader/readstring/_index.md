---
title: "System::Xml::XmlNodeReader::ReadString‑metod"
linktitle: "ReadString"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeReader::ReadString‑metod. Läser innehållet i ett element eller textnod som en sträng i C++."
type: docs
weight: 3600
url: /sv/cpp/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString method


Läser innehållet i ett element eller en textnod som en sträng.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```


### ReturnValue

Innehållet i elementet eller den textliknande noden (Det kan inkludera CDATA, [Text](../../../system.text/) noder och så vidare). Detta kan vara en tom sträng om läsaren är placerad på något annat än ett element eller en textnod, eller om det inte finns mer textinnehåll att returnera i det aktuella sammanhanget. Obs: Textnoden kan vara antingen ett element eller ett attribut‑textnod.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
