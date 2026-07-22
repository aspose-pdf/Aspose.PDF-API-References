---
title: "System::Xml::XmlWriter::WriteProcessingInstruction metod"
linktitle: "WriteProcessingInstruction"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlWriter::WriteProcessingInstruction metod. När den åsidosätts i en avledd klass skriver den ut en bearbetningsinstruktion med ett mellanslag mellan namn och text enligt följande: <?name text?> i C++."
type: docs
weight: 2700
url: /sv/cpp/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction method


När den åsidosätts i en avledd klass skriver den ut en bearbetningsinstruktion med ett mellanslag mellan namn och text enligt följande: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Namnet på bearbetningsinstruktionen. |
| text | String | Texten att inkludera i bearbetningsinstruktionen. |
## Anmärkningar



Denna metod används för att skapa en XML-deklaration efter att [XmlWriter::WriteStartDocument](../writestartdocument/) redan har anropats.
## Se även

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
