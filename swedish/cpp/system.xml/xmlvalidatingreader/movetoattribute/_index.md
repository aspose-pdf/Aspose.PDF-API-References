---
title: "System::Xml::XmlValidatingReader::MoveToAttribute metod"
linktitle: "MoveToAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlValidatingReader::MoveToAttribute metod. Flyttar till attributet med det angivna indexet i C++."
type: docs
weight: 3500
url: /sv/cpp/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(int32_t) method


Flyttar till attributet med det angivna indexet.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int32_t | Indexet för attributet. |

## Se även

* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::MoveToAttribute(String, String) method


Flyttar till attributet med det angivna lokala namnet och namnrymdens Uniform Resource Identifier (URI).

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det lokala namnet på attributet. |
| namespaceURI | String | Namnrymds-URI:n för attributet. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## Se även

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::MoveToAttribute(String) method


Flyttar till attributet med det angivna namnet.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på attributet. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## Se även

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
