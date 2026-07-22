---
title: "System::Xml::XmlDocument::Load‑metod"
linktitle: "ReadAttributeValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "Load"
type: docs
weight: 3800
url: /sv/cpp/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue method


System::Xml::XmlDocument::Load‑metod. Laddar XML-dokumentet från den angivna strömmen i C++.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### ReturnValue

**true** if there are nodes to return. **false** if the reader is not positioned on an attribute node when the initial call is made or if all the attribute values have been read. An empty attribute, such as, **misc=""**, returns **true** with a single node with a value of [String::Empty](../../../system/string/empty/).

## Se även

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
