---
title: "System::Xml::XmlTextWriter::WriteProcessingInstruction‑metod"
linktitle: "WriteProcessingInstruction"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextWriter::WriteProcessingInstruction‑metod. Skriver ut en bearbetningsinstruktion med ett mellanslag mellan namn och text enligt följande: <?name text?> i C++."
type: docs
weight: 3300
url: /sv/cpp/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction method


Skriver ut en processinstruktion med ett mellanslag mellan namn och text enligt följande: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Namnet på bearbetningsinstruktionen. |
| text | String | [Text](../../../system.text/) att inkludera i bearbetningsinstruktionen. |
## Anmärkningar



Denna metod används för att skapa en XML-deklaration efter att [XmlTextWriter::WriteStartDocument](../writestartdocument/) redan har anropats.
## Se även

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
