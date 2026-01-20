---
title: System::Xml::XmlTextWriter::WriteProcessingInstruction method
linktitle: WriteProcessingInstruction
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextWriter::WriteProcessingInstruction method. Writes out a processing instruction with a space between the name and text as follows: <?name text?> in C++.'
type: docs
weight: 3300
url: /cpp/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction method


Writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Name of the processing instruction. |
| text | String | [Text](../../../system.text/) to include in the processing instruction. |
## Remarks



This method is being used to create an XML declaration after [XmlTextWriter::WriteStartDocument](../writestartdocument/) has already been called. 
## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
