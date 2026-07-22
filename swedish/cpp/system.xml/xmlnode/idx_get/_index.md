---
title: "System::Xml::XmlNode::idx_get metod"
linktitle: "idx_get"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNode::idx_get metod. Returnerar det första barn-elementet med de angivna XmlNode::get_LocalName- och XmlNode::get_NamespaceURI-värdena i C++."
type: docs
weight: 3000
url: /sv/cpp/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String, String) method


Returnerar det första barn-elementet med de angivna [XmlNode::get_LocalName](../get_localname/) och [XmlNode::get_NamespaceURI](../get_namespaceuri/) värdena.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lokalnamn | String | Det lokala namnet på elementet. |
| ns | String | Namnrymdens URI för elementet. |

### ReturnValue

Den första [XmlElement](../../xmlelement/) med matchande **localname** och **ns**. Den returnerar **nullptr** om det inte finns någon match.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNode::idx_get(String) method


Returnerar det första barn-elementet med den angivna [XmlNode::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på elementet som ska hämtas. |

### ReturnValue

Den första [XmlElement](../../xmlelement/) som matchar det angivna namnet. Den returnerar **nullptr** om det inte finns någon match.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
