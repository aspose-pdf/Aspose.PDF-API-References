---
title: "System::Xml::XPath::XPathNavigator::MoveToChild metod"
linktitle: "MoveToChild"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathNavigator::MoveToChild metod. Flyttar XPathNavigator till barnnoden med det lokala namnet och namnrymds‑URI som anges i C++."
type: docs
weight: 5200
url: /sv/cpp/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) method


Flyttar [XPathNavigator](../) till barnnoden med det lokala namnet och namnrymds‑URI som anges.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det lokala namnet på barnnoden att flytta till. |
| namespaceURI | String | Namnrums‑URI för barnnoden att flytta till. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the child node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## Se även

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToChild(XPathNodeType) method


Flyttar [XPathNavigator](../) till barnnoden av den angivna [XPathNodeType](../../xpathnodetype/).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | XPathNodeType | [XPathNodeType](../../xpathnodetype/) för barnnoden att flytta till. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the child node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## Se även

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
