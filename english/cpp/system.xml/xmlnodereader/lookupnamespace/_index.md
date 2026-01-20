---
title: System::Xml::XmlNodeReader::LookupNamespace method
linktitle: LookupNamespace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeReader::LookupNamespace method. Resolves a namespace prefix in the current element''s scope in C++.'
type: docs
weight: 2500
url: /cpp/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace method


Resolves a namespace prefix in the current element's scope.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const String\& | The prefix whose namespace URI you want to resolve. To match the default namespace, pass an empty string. This string does not have to be atomized. |

### ReturnValue

The namespace URI to which the prefix maps or **nullptr** if no matching prefix is found.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
