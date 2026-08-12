---
title: "System::Xml::XmlReader::ReadToNextSibling‑metod"
linktitle: "ReadToNextSibling"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::ReadToNextSibling‑metod. Flyttar XmlReader till nästa syskon‑element med det angivna lokala namnet och namnrymds‑URI:n i C++."
type: docs
weight: 7300
url: /sv/cpp/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String, String) method


Flyttar [XmlReader](../) till nästa syskon‑element med det angivna lokala namnet och namnrymds‑URI:n.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det lokala namnet på syskon‑elementet du vill flytta till. |
| namespaceURI | String | Namnrums‑URI:n för syskon‑elementet du vill flytta till. |

### ReturnValue

**true** if a matching sibling element is found; otherwise, **false**. If a matching sibling element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the parent element.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadToNextSibling(String) method


Flyttar [XmlReader](../) till nästa syskon‑element med det angivna kvalificerade namnet.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på syskon‑elementet du vill flytta till. |

### ReturnValue

**true** if a matching sibling element is found; otherwise **false**. If a matching sibling element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the parent element.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
