---
title: "System::Xml::XmlDocument::CreateAttribute metod"
linktitle: "CreateAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocument::CreateAttribute metod. Skapar ett XmlAttribute med det angivna namnet i C++."
type: docs
weight: 300
url: /sv/cpp/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) method


Skapar ett [XmlAttribute](../../xmlattribute/) med det angivna namnet.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const String\& | Det kvalificerade namnet på attributet. Om namnet innehåller ett kolon visar värdet från [XmlNode::get_Prefix](../../xmlnode/get_prefix/) delen av namnet som föregår det första kolonet och värdet från [XmlDocument::get_LocalName](../get_localname/) delen som följer efter det första kolonet. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) förblir tomt om inte prefixet är ett erkänt inbyggt prefix såsom **xmlns**. I detta fall har get_NamespaceURI värdet [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### ReturnValue

Den nya [XmlAttribute](../../xmlattribute/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) method


Skapar ett [XmlAttribute](../../xmlattribute/) med det angivna [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const String\& | Prefixet för attributet (om något). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |
| localName | const String\& | Det lokala namnet på attributet. |
| namespaceURI | const String\& | Namespace‑URI:n för attributet (om någon). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. Om **prefix** är **xmlns**, måste denna parameter vara [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) annars kastas ett undantag. |

### ReturnValue

Den nya [XmlAttribute](../../xmlattribute/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateAttribute(const String\&, const String\&) method


Skapar ett [XmlAttribute](../../xmlattribute/) med det angivna kvalificerade namnet och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| qualifiedName | const String\& | Det kvalificerade namnet på attributet. Om namnet innehåller ett kolon kommer värdet från [XmlNode::get_Prefix](../../xmlnode/get_prefix/) att visa delen av namnet som föregår kolonet och värdet från [XmlDocument::get_LocalName](../get_localname/) att visa delen efter kolonet. |
| namespaceURI | const String\& | NamespaceURI:n för attributet. Om det kvalificerade namnet innehåller ett prefix **xmlns**, måste denna parameter vara [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### ReturnValue

Den nya [XmlAttribute](../../xmlattribute/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
