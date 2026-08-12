---
title: "System::Xml::XmlReader::idx_get metod"
linktitle: "idx_get"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::idx_get metod. När den åsidosätts i en avledd klass hämtas värdet på attributet med det angivna indexet i C++."
type: docs
weight: 2900
url: /sv/cpp/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) method


När den åsidosätts i en avledd klass, hämtar den värdet på attributet med det angivna indexet.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int32_t | Indexet för attributet. |

### ReturnValue

Värdet för det angivna attributet.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::idx_get(String) method


När den åsidosätts i en avledd klass hämtas värdet på attributet med det angivna [XmlReader::get_Name](../get_name/) värdet.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på attributet. |

### ReturnValue

Värdet för det angivna attributet. Om attributet inte hittas, returneras **nullptr**.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::idx_get(String, String) method


När den åsidosätts i en avledd klass hämtas värdet på attributet med de angivna [XmlReader::get_LocalName](../get_localname/) och [XmlReader::get_NamespaceURI](../get_namespaceuri/) värdena.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det lokala namnet på attributet. |
| namespaceURI | String | Namnrymds-URI:n för attributet. |

### ReturnValue

Värdet för det angivna attributet. Om attributet inte hittas, returneras **nullptr**.

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
