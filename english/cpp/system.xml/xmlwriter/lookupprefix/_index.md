---
title: System::Xml::XmlWriter::LookupPrefix method
linktitle: LookupPrefix
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlWriter::LookupPrefix method. When overridden in a derived class, returns the closest prefix defined in the current namespace scope for the namespace URI in C++.'
type: docs
weight: 800
url: /cpp/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix method


When overridden in a derived class, returns the closest prefix defined in the current namespace scope for the namespace URI.

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| ns | String | The namespace URI whose prefix you want to find. |

### ReturnValue

The matching prefix or **nullptr** if no matching namespace URI is found in the current scope.

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
