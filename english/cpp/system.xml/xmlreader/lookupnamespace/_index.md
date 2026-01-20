---
title: System::Xml::XmlReader::LookupNamespace method
linktitle: LookupNamespace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::LookupNamespace method. When overridden in a derived class, resolves a namespace prefix in the current element''s scope in C++.'
type: docs
weight: 3100
url: /cpp/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace method


When overridden in a derived class, resolves a namespace prefix in the current element's scope.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const String\& | The prefix whose namespace URI you want to resolve. To match the default namespace, pass an empty string. |

### ReturnValue

The namespace URI to which the prefix maps or **nullptr** if no matching prefix is found.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
