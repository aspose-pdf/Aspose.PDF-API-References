---
title: "System::Xml::XmlDocument::GetElementsByTagName metod"
linktitle: "GetElementsByTagName"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocument::GetElementsByTagName metod. Returnerar en XmlNodeList som innehåller en lista över alla underordnade element som matchar den angivna XmlDocument::get_LocalName och XmlNode::get_NamespaceURI i C++."
type: docs
weight: 3200
url: /sv/cpp/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String, String) method


Returnerar en [XmlNodeList](../../xmlnodelist/) som innehåller en lista över alla underordnade element som matchar den angivna [XmlDocument::get_LocalName](../get_localname/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det LocalName att matcha. Det speciella värdet **\"*\"** matchar alla taggar. |
| namespaceURI | String | NamespaceURI att matcha. |

### ReturnValue

En [XmlNodeList](../../xmlnodelist/) som innehåller en lista över alla matchande noder. Om inga noder matchar den angivna **localName** och **namespaceURI**, blir den returnerade samlingen tom.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::GetElementsByTagName(String) method


Returnerar en [XmlNodeList](../../xmlnodelist/) som innehåller en lista över alla underordnade element som matchar det angivna namnet.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet att matcha. Det matchas mot **get_Name**-värdet för den matchande noden. Det speciella värdet **\"*\"** matchar alla taggar. |

### ReturnValue

En [XmlNodeList](../../xmlnodelist/) som innehåller en lista över alla matchande noder. Om inga noder matchar **name**, blir den returnerade samlingen tom.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
