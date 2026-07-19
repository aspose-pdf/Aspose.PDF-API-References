---
title: "System::Xml::XmlNodeReader::ReadAttributeValue метод"
linktitle: "ReadAttributeValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNodeReader::ReadAttributeValue метод. Разбирает значение атрибута в один или несколько узлов Text, EntityReference или EndEntity в C++."
type: docs
weight: 3100
url: /ru/cpp/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue method


Разбирает значение атрибута в один или несколько **[Text](../../../system.text/)**, **EntityReference**, или **EndEntity** узлов.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```


### ReturnValue

**true** if there are nodes to return. **false** if the reader is not positioned on an attribute node when the initial call is made or if all the attribute values have been read. An empty attribute, such as, **misc=""**, returns **true** with a single node with a value of [String::Empty](../../../system/string/empty/).

## См. также

* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
