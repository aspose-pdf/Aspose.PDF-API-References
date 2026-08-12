---
title: "System::Xml::XmlNodeReader::GetAttribute metod"
linktitle: "GetAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeReader::GetAttribute metod. Returnerar värdet för attributet med det angivna indexet i C++."
type: docs
weight: 2400
url: /sv/cpp/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(int32_t) method


Returnerar värdet på attributet med det angivna indexet.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attributeIndex | int32_t | Indexet för attributet. Indexet är nollbaserat. (Det första attributet har index 0.) |

### ReturnValue

Värdet för det angivna attributet.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::GetAttribute(String) method


Returnerar värdet på attributet med det angivna namnet.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på attributet. |

### ReturnValue

Värdet för det angivna attributet. Om attributet inte hittas, returneras **nullptr**.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::GetAttribute(String, String) method


Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det lokala namnet på attributet. |
| namespaceURI | String | Namnrymds-URI:n för attributet. |

### ReturnValue

Värdet för det angivna attributet. Om attributet inte hittas, returneras **nullptr**.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
