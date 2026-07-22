---
title: "System::Xml::XmlWriter::WriteDocType metod"
linktitle: "WriteDocType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlWriter::WriteDocType metod. När den åsidosätts i en avledd klass skriver den DOCTYPE-deklarationen med det angivna namnet och valfria attribut i C++."
type: docs
weight: 1700
url: /sv/cpp/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType method


När den åsidosätts i en avledd klass skriver den DOCTYPE-deklarationen med det angivna namnet och valfria attribut.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | const String\& | Namnet på DOCTYPE. Detta får inte vara tomt. |
| pubid | const String\& | Om den inte är null skriver den också PUBLIC "pubid" "sysid" där **pubid** och **sysid** ersätts med värdet för de givna argumenten. |
| sysid | const String\& | Om **pubid** är **nullptr** och **sysid** är icke‑null skriver den SYSTEM "sysid" där **sysid** ersätts med värdet för detta argument. |
| subset | const String\& | Om icke-null skriver den [subset] där subset ersätts med värdet för detta argument. |

## Se även

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
