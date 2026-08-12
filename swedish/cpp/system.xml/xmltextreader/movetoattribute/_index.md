---
title: "System::Xml::XmlTextReader::MoveToAttribute metod"
linktitle: "MoveToAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextReader::MoveToAttribute metod. Flyttar till attributet med det angivna indexet i C++."
type: docs
weight: 3800
url: /sv/cpp/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(int32_t) method


Flyttar till attributet med det angivna indexet.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int32_t | Indexet för attributet. |

## Se även

* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::MoveToAttribute(String, String) method


Flyttar till attributet med det angivna lokala namnet och namnrymdens URI.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det lokala namnet på attributet. |
| namespaceURI | String | Namnrymds-URI:n för attributet. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Se även

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::MoveToAttribute(String) method


Flyttar till attributet med det angivna namnet.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Det kvalificerade namnet på attributet. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Se även

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
