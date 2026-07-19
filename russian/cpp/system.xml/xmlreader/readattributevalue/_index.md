---
title: "System::Xml::XmlReader::ReadAttributeValue method"
linktitle: "ReadAttributeValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadAttributeValue method. При переопределении в производном классе разбирает значение атрибута в один или несколько узлов Text, EntityReference или EndEntity в C++."
type: docs
weight: 3800
url: /ru/cpp/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue method


При переопределении в производном классе разбирает значение атрибута в один или несколько узлов **[Text](../../../system.text/)**, **EntityReference** или **EndEntity**.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### ReturnValue

**true** if there are nodes to return. **false** if the reader is not positioned on an attribute node when the initial call is made or if all the attribute values have been read. An empty attribute, such as, **misc=""**, returns **true** with a single node with a value of [String::Empty](../../../system/string/empty/).

## См. также

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
