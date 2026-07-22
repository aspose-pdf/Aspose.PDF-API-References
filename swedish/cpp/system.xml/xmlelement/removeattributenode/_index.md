---
title: "System::Xml::XmlElement::RemoveAttributeNode metod"
linktitle: "RemoveAttributeNode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlElement::RemoveAttributeNode metod. Tar bort den angivna XmlAttribute i C++."
type: docs
weight: 2100
url: /sv/cpp/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) method


Tar bort den angivna [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldAttr | SharedPtr\<XmlAttribute\> | [XmlAttribute](../../xmlattribute/)-noden att ta bort. Om det borttagna attributet har ett standardvärde ersätts det omedelbart. |

### ReturnValue

Det borttagna [XmlAttribute](../../xmlattribute/) eller **nullptr** om **oldAttr** inte är en attributnod till [XmlElement](../).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::RemoveAttributeNode(String, String) method


Tar bort den [XmlAttribute](../../xmlattribute/) som anges av det lokala namnet och namnrymds-URI:n. (Om det borttagna attributet har ett standardvärde ersätts det omedelbart).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det lokala namnet på attributet. |
| namespaceURI | String | Namnrymds-URI:n för attributet. |

### ReturnValue

Den borttagna [XmlAttribute](../../xmlattribute/) eller **nullptr** om [XmlElement](../) inte har någon matchande attributnod.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
