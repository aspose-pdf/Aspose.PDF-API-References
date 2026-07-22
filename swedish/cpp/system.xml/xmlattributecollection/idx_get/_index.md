---
title: "System::Xml::XmlAttributeCollection::idx_get metod"
linktitle: "idx_get"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlAttributeCollection::idx_get‑metod. Returnerar attributet med det angivna lokala namnet och namnrymdens Uniform Resource Identifier (URI) i C++."
type: docs
weight: 300
url: /sv/cpp/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(const String\&, const String\&) method


Returnerar attributet med det angivna lokala namnet och namnrymdens Uniform Resource Identifier (URI).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | const String\& | Det lokala namnet på attributet. |
| namespaceURI | const String\& | Namnrymds-URI:n för attributet. |

### ReturnValue

Attributet med det angivna lokala namnet och namnrymdens URI. Om attributet inte finns, returnerar den här metoden **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlAttributeCollection::idx_get(const String\&) method


Returnerar attributet med det angivna namnet.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | const String\& | Det kvalificerade namnet på attributet. |

### ReturnValue

Attributet med det angivna namnet. Om attributet inte finns, returnerar den här metoden **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlAttributeCollection::idx_get(int32_t) method


Returnerar attributet med det angivna indexet.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int32_t | Indexet för attributet. |

### ReturnValue

Attributet på det angivna indexet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
