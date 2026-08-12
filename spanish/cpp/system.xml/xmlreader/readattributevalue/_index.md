---
title: "System::Xml::XmlReader::ReadAttributeValue método"
linktitle: "ReadAttributeValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlReader::ReadAttributeValue método. Cuando se sobrescribe en una clase derivada, analiza el valor del atributo en uno o más nodos Text, EntityReference o EndEntity en C++."
type: docs
weight: 3800
url: /es/cpp/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue method


Cuando se sobrescribe en una clase derivada, analiza el valor del atributo en uno o más nodos **[Text](../../../system.text/)**, **EntityReference**, o **EndEntity**.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### ReturnValue

**true** if there are nodes to return. **false** if the reader is not positioned on an attribute node when the initial call is made or if all the attribute values have been read. An empty attribute, such as, **misc=""**, returns **true** with a single node with a value of [String::Empty](../../../system/string/empty/).

## Ver también

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
