---
title: "System::Xml::XmlDocument::CreateElement‑metod"
linktitle: "CreateElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocument::CreateElement‑metod. Skapar ett element med det angivna namnet i C++."
type: docs
weight: 800
url: /sv/cpp/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) method


Skapar ett element med det angivna namnet.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const String\& | Det kvalificerade namnet på elementet. Om namnet innehåller ett kolon så visar värdet från [XmlNode::get_Prefix](../../xmlnode/get_prefix/) delen av namnet som föregår kolonet och värdet från [XmlDocument::get_LocalName](../get_localname/) visar delen av namnet efter kolonet. Det kvalificerade namnet får inte innehålla ett prefix av **xmlns**. |

### ReturnValue

Det nya [XmlElement](../../xmlelement/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateElement(const String\&, const String\&, const String\&) method


Skapar ett element med den angivna [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const String\& | Prefixet för det nya elementet (om något). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |
| localName | const String\& | Det lokala namnet på det nya elementet. |
| namespaceURI | const String\& | Namnutrymmet URI för det nya elementet (om något). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |

### ReturnValue

Det nya [XmlElement](../../xmlelement/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateElement(const String\&, const String\&) method


Skapar ett [XmlElement](../../xmlelement/) med det kvalificerade namnet och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| qualifiedName | const String\& | Det kvalificerade namnet på elementet. Om namnet innehåller ett kolon kommer värdet från [XmlNode::get_Prefix](../../xmlnode/get_prefix/) att visa delen av namnet som föregår kolonet och värdet från [XmlDocument::get_LocalName](../get_localname/) att visa delen av namnet efter kolonet. Det kvalificerade namnet får inte innehålla ett prefix av **xmlns**. |
| namespaceURI | const String\& | Namnrymdens URI för elementet. |

### ReturnValue

Det nya [XmlElement](../../xmlelement/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
