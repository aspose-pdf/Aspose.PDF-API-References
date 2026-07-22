---
title: "System::Xml::XmlNodeReader::MoveToAttribute metod"
linktitle: "MoveToAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeReader::MoveToAttribute metod. Flyttar till attributet med det angivna indexet i C++."
type: docs
weight: 2600
url: /sv/cpp/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(int32_t) method


Flyttar till attributet med det angivna indexet.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attributeIndex | int32_t | Indexet för attributet. |

## Se även

* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::MoveToAttribute(String) method


Flyttar till attributet med det angivna namnet.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på attributet. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::MoveToAttribute(String, String) method


Flyttar till attributet med det angivna lokala namnet och namnrymdens URI.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det lokala namnet på attributet. |
| namespaceURI | String | Namnrymds-URI:n för attributet. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
