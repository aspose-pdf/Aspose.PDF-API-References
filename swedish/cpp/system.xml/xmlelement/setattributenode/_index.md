---
title: "System::Xml::XmlElement::SetAttributeNode metod"
linktitle: "SetAttributeNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlElement::SetAttributeNode metod. Lägger till den angivna XmlAttribute i C++."
type: docs
weight: 2700
url: /sv/cpp/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) method


Lägger till den angivna [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newAttr | SharedPtr\<XmlAttribute\> | Den [XmlAttribute](../../xmlattribute/)-noden att lägga till i attributsamlingen för detta element. |

### ReturnValue

Om attributet ersätter ett befintligt attribut med samma namn, returneras det gamla [XmlAttribute](../../xmlattribute/); annars returneras **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::SetAttributeNode(String, String) method


Lägger till den angivna [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det lokala namnet på attributet. |
| namespaceURI | String | Namnrymds-URI:n för attributet. |

### ReturnValue

Den [XmlAttribute](../../xmlattribute/) att lägga till.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
