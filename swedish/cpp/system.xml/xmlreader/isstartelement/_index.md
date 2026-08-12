---
title: "System::Xml::XmlReader::IsStartElement metod"
linktitle: "IsStartElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::IsStartElement metod. Anropar XmlReader::MoveToContent och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg i C++."
type: docs
weight: 3000
url: /sv/cpp/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() method


Anropar [XmlReader::MoveToContent](../movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```


### ReturnValue

**true** if [XmlReader::MoveToContent](../movetocontent/) finds a start tag or empty element tag; **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found.

## Se även

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::IsStartElement(String, String) method


Anropar [XmlReader::MoveToContent](../movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg samt om värdena för [XmlReader::get_LocalName](../get_localname/) och [XmlReader::get_NamespaceURI](../get_namespaceuri/) för det hittade elementet matchar de angivna strängarna.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lokalnamn | String | Strängen att matcha mot **LocalName**-värdet för det hittade elementet. |
| ns | String | Strängen att matcha mot **NamespaceURI**-värdet för det hittade elementet. |

### ReturnValue

**true** if the resulting node is an element. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the **LocalName** and **NamespaceURI** values of the element do not match the specified strings.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::IsStartElement(String) method


Anropar [XmlReader::MoveToContent](../movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg samt om värdet för [XmlReader::get_Name](../get_name/) för det hittade elementet matchar det givna argumentet.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Strängen som matchas mot **Name**-värdet för det hittade elementet. |

### ReturnValue

**true** if the resulting node is an element and the **Name** value matches the specified string. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the element **Name** value does not match the specified string.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
