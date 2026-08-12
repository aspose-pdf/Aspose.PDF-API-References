---
title: "System::Xml::XmlReader::GetAttribute‑metod"
linktitle: "GetAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::GetAttribute‑metod. När den åsidosätts i en avledd klass hämtar den värdet för attributet med det angivna indexet i C++."
type: docs
weight: 2800
url: /sv/cpp/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(int32_t) method


När den åsidosätts i en avledd klass, hämtar den värdet på attributet med det angivna indexet.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int32_t | Indexet för attributet. Indexet är nollbaserat. (Det första attributet har index 0.) |

### ReturnValue

Värdet på det angivna attributet. Denna metod flyttar inte läsaren.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::GetAttribute(String) method


När den åsidosätts i en avledd klass hämtas värdet på attributet med det angivna [XmlReader::get_Name](../get_name/) värdet.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på attributet. |

### ReturnValue

Värdet på det angivna attributet. Om attributet inte hittas eller värdet är [String::Empty](../../../system/string/empty/), returneras **nullptr**.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::GetAttribute(String, String) method


När den åsidosätts i en avledd klass hämtas värdet på attributet med de angivna [XmlReader::get_LocalName](../get_localname/) och [XmlReader::get_NamespaceURI](../get_namespaceuri/) värdena.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det lokala namnet på attributet. |
| namespaceURI | String | Namnrymds-URI:n för attributet. |

### ReturnValue

Värdet på det angivna attributet. Om attributet inte hittas eller värdet är [String::Empty](../../../system/string/empty/), returneras **nullptr**. Denna metod flyttar inte läsaren.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
