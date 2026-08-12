---
title: "System::Xml::XmlNameTable::Add metod"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNameTable::Add metod. När den åsidosätts i en avledd klass atomiserar den den angivna strängen och lägger till den i XmlNameTable i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


När den åsidosätts i en avledd klass atomiserar den den angivna strängen och lägger till den i [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const ArrayPtr\<char16_t\>\& | Teckenarrayen som innehåller namnet att lägga till. |
| förskjutning | int32_t | Nollbaserat index i arrayen som anger det första tecknet i namnet. |
| längd | int32_t | Antalet tecken i namnet. |

### ReturnValue

Den nya atomiserade strängen eller den befintliga om den redan finns. Om längden är noll, returneras [String::Empty](../../../system/string/empty/).

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNameTable::Add(const String\&) method


När den åsidosätts i en avledd klass atomiserar den den angivna strängen och lägger till den i [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const String\& | Namnet att lägga till. |

### ReturnValue

Den nya atomiserade strängen eller den befintliga om den redan finns.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
