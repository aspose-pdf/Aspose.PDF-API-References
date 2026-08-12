---
title: "Метод System::Xml::XmlTextReader::ReadAttributeValue"
linktitle: "ReadAttributeValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlTextReader::ReadAttributeValue. Разбирает значение атрибута в один или несколько узлов Text, EntityReference или EndEntity в C++."
type: docs
weight: 4300
url: /ru/cpp/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue method


Разбирает значение атрибута в один или несколько **[Text](../../../system.text/)**, **EntityReference**, или **EndEntity** узлов.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```


### ReturnValue

**true** if there are nodes to return. **false** if the reader is not positioned on an attribute node when the initial call is made or if all the attribute values have been read. An empty attribute, such as, **misc=""**, returns **true** with a single node with a value of [String::Empty](../../../system/string/empty/).

## См. также

* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
