---
title: System::Xml::XPath::XPathNavigator::LookupPrefix method
linktitle: LookupPrefix
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::LookupPrefix method. Returns the prefix declared for the specified namespace URI in C++.'
type: docs
weight: 4800
url: /cpp/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix method


Returns the prefix declared for the specified namespace URI.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | const String\& | The namespace URI to resolve for the prefix. |

### ReturnValue

A [String](../../../system/string/) that contains the namespace prefix assigned to the namespace URI specified; otherwise, [String::Empty](../../../system/string/empty/) if no prefix is assigned to the namespace URI specified. The [String](../../../system/string/) returned is atomized.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
