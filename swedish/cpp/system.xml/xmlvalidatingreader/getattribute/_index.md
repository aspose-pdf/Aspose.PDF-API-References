---
title: "System::Xml::XmlValidatingReader::GetAttribute-metod"
linktitle: "GetAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlValidatingReader::GetAttribute-metod. Returnerar värdet på attributet med det angivna indexet i C++."
type: docs
weight: 3200
url: /sv/cpp/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(int32_t) method


Returnerar värdet på attributet med det angivna indexet.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int32_t | Indexet för attributet. Indexet är nollbaserat. (Det första attributet har index 0.) |

### ReturnValue

Värdet för det angivna attributet.

## Se även

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::GetAttribute(String, String) method


Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens Uniform Resource Identifier (URI).

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det lokala namnet på attributet. |
| namespaceURI | String | Namnrymds-URI:n för attributet. |

### ReturnValue

Värdet på det angivna attributet. Om attributet inte hittas returneras **nullptr**. Denna metod flyttar inte läsaren.

## Se även

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::GetAttribute(String) method


Returnerar värdet på attributet med det angivna namnet.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på attributet. |

### ReturnValue

Värdet för det angivna attributet. Om attributet inte hittas, returneras **nullptr**.

## Se även

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
