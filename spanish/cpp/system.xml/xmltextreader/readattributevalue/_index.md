---
title: "System::Xml::XmlTextReader::ReadAttributeValue método"
linktitle: "ReadAttributeValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlTextReader::ReadAttributeValue método. Analiza el valor del atributo en uno o más nodos Text, EntityReference o EndEntity en C++."
type: docs
weight: 4300
url: /es/cpp/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue method


Analiza el valor del atributo en uno o más **[Text](../../../system.text/)**, **EntityReference**, o **EndEntity** nodos.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```


### ReturnValue

**true** if there are nodes to return. **false** if the reader is not positioned on an attribute node when the initial call is made or if all the attribute values have been read. An empty attribute, such as, **misc=""**, returns **true** with a single node with a value of [String::Empty](../../../system/string/empty/).

## Ver también

* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
