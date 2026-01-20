---
title: System::Xml::XmlTextWriter::LookupPrefix method
linktitle: LookupPrefix
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextWriter::LookupPrefix method. Returns the closest prefix defined in the current namespace scope for the namespace URI in C++.'
type: docs
weight: 1300
url: /cpp/system.xml/xmltextwriter/lookupprefix/
---
## XmlTextWriter::LookupPrefix method


Returns the closest prefix defined in the current namespace scope for the namespace URI.

```cpp
String System::Xml::XmlTextWriter::LookupPrefix(String ns) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| ns | String | Namespace URI whose prefix you want to find. |

### ReturnValue

The matching prefix. Or **nullptr** if no matching namespace URI is found in the current scope.

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
