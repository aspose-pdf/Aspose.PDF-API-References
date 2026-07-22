---
title: "System::Xml::XmlValidatingReader::ReadAttributeValue metod"
linktitle: "ReadAttributeValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlValidatingReader::ReadAttributeValue metod. Tolkar attributvärdet till en eller flera Text-, EntityReference- eller EndEntity‑noder i C++."
type: docs
weight: 4000
url: /sv/cpp/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue method


Tolkar attributvärdet till en eller flera **[Text](../../../system.text/)**, **EntityReference**, eller **EndEntity**‑noder.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```


### ReturnValue

**true** if there are nodes to return. **false** if the reader is not positioned on an attribute node when the initial call is made or if all the attribute values have been read. An empty attribute, such as, **misc=""**, returns **true** with a single node with a value of [String::Empty](../../../system/string/empty/).

## Se även

* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
