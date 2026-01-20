---
title: System::Xml::XPath::XPathNavigator::LookupNamespace method
linktitle: LookupNamespace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::LookupNamespace method. Returns the namespace URI for the specified prefix in C++.'
type: docs
weight: 4700
url: /cpp/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace method


Returns the namespace URI for the specified prefix.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const String\& | The prefix whose namespace URI you want to resolve. To match the default namespace, pass [String::Empty](../../../system/string/empty/). |

### ReturnValue

A [String](../../../system/string/) that contains the namespace URI assigned to the namespace prefix specified; **nullptr** if no namespace URI is assigned to the prefix specified. The [String](../../../system/string/) returned is atomized.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
