---
title: "System::Xml::XmlDocument::CreateNode metod"
linktitle: "CreateNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocument::CreateNode metod. Skapar ett XmlNode med den angivna nodtypen, XmlDocument::get_Name och XmlNode::get_NamespaceURI i C++."
type: docs
weight: 1100
url: /sv/cpp/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(const String\&, const String\&, const String\&) method


Skapar ett [XmlNode](../../xmlnode/) med den angivna nodtypen, [XmlDocument::get_Name](../get_name/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeTypeString | const String\& | [String](../../../system/string/) version av [XmlNodeType](../../xmlnodetype/) för den nya noden. Denna parameter måste vara ett av värdena som listas i tabellen nedan. |
| name | const String\& | Det kvalificerade namnet på den nya noden. Om namnet innehåller ett kolon parsas det till komponenterna [XmlNode::get_Prefix](../../xmlnode/get_prefix/) och [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const String\& | Namespace‑URI:n för den nya noden. |

### ReturnValue

Den nya [XmlNode](../../xmlnode/).
## Anmärkningar



Parametern **nodeTypeString** är skiftlägeskänslig och måste vara ett av värdena i följande tabell: |||
|-|-|
| nodeTypeString | XmlNodeType |
| attribut | Attribute |
| cdatasektion | CDATA |
| kommentar | Comment |
| dokument | Document |
| dokumentfragment | DocumentFragment |
| dokumenttyp | DocumentType |
| element | Element |
| entitetsreferens | EntityReference |
| processinstruktion | ProcessingInstruction |
| betydande mellanslag | SignificantWhitespace |
| text | Text |
| mellanslag | Whitespace |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) method


Skapar en [XmlNode](../../xmlnode/) med den angivna [XmlNodeType](../../xmlnodetype/), [XmlDocument::get_Name](../get_name/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | XmlNodeType | Den [XmlNodeType](../../xmlnodetype/) för den nya noden. |
| name | const String\& | Det kvalificerade namnet på den nya noden. Om namnet innehåller ett kolon parsas det då till komponenterna [XmlNode::get_Prefix](../../xmlnode/get_prefix/) och [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const String\& | Namespace‑URI:n för den nya noden. |

### ReturnValue

Den nya [XmlNode](../../xmlnode/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) method


Skapar en [XmlNode](../../xmlnode/) med den angivna [XmlNodeType](../../xmlnodetype/), [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | XmlNodeType | Den [XmlNodeType](../../xmlnodetype/) för den nya noden. |
| prefix | const String\& | Prefixet för den nya noden. |
| namn | const String\& | Det lokala namnet på den nya noden. |
| namespaceURI | const String\& | Namespace‑URI:n för den nya noden. |

### ReturnValue

Den nya [XmlNode](../../xmlnode/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
