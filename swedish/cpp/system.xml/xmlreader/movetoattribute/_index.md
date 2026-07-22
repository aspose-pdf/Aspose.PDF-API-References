---
title: "System::Xml::XmlReader::MoveToAttribute metod"
linktitle: "MoveToAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::MoveToAttribute metod. När den åsidosätts i en avledd klass, flyttar den till attributet med det angivna indexet i C++."
type: docs
weight: 3200
url: /sv/cpp/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(int32_t) method


När den åsidosätts i en avledd klass, flyttar den till attributet med det angivna indexet.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int32_t | Indexet för attributet. |

## Se även

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::MoveToAttribute(String) method


När den åsidosätts i en avledd klass, flyttar den till attributet med det angivna [XmlReader::get_Name](../get_name/) värdet.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på attributet. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::MoveToAttribute(String, String) method


När den åsidosätts i en avledd klass, flyttar den till attributet med de angivna [XmlReader::get_LocalName](../get_localname/) och [XmlReader::get_NamespaceURI](../get_namespaceuri/) värdena.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det lokala namnet på attributet. |
| ns | String | Namnrymds-URI:n för attributet. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
