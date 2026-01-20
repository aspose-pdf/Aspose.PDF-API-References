---
title: System::Xml::XmlTextReader::LookupNamespace method
linktitle: LookupNamespace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextReader::LookupNamespace method. Resolves a namespace prefix in the current element''s scope in C++.'
type: docs
weight: 3700
url: /cpp/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace method


Resolves a namespace prefix in the current element's scope.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const String\& | The prefix whose namespace URI you want to resolve. To match the default namespace, pass an empty string. This string does not have to be atomized. |

### ReturnValue

The namespace URI to which the prefix maps or **nullptr** if no matching prefix is found.

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
