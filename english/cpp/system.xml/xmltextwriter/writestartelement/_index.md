---
title: System::Xml::XmlTextWriter::WriteStartElement method
linktitle: WriteStartElement
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextWriter::WriteStartElement method. Writes the specified start tag and associates it with the given namespace and prefix in C++.'
type: docs
weight: 3800
url: /cpp/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement method


Writes the specified start tag and associates it with the given namespace and prefix.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const String\& | The namespace prefix of the element. |
| localName | const String\& | The local name of the element. |
| ns | const String\& | The namespace URI to associate with the element. If this namespace is already in scope and has an associated prefix then the writer automatically writes that prefix also. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
