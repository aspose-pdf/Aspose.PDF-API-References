---
title: "System::Xml::XmlNameTable::Get metod"
linktitle: "Get"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNameTable::Get metod. När den åsidosätts i en avledd klass, hämtar den den atomiserade strängen som innehåller samma tecken som det angivna teckensegmentet i den givna arrayen i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


När den åsidosätts i en avledd klass, får den den atomiserade strängen som innehåller samma tecken som det angivna teckensegmentet i den givna arrayen.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const ArrayPtr\<char16_t\>\& | Teckenarrayen som innehåller namnet att slå upp. |
| förskjutning | int32_t | Det nollbaserade indexet i arrayen som specificerar det första tecknet i namnet. |
| längd | int32_t | Antalet tecken i namnet. |

### ReturnValue

Den atomiserade strängen eller **nullptr** om strängen ännu inte har atomiserats. Om **length** är noll, returneras [String::Empty](../../../system/string/empty/).

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNameTable::Get(const String\&) method


När den åsidosätts i en avledd klass, får den den atomiserade strängen som innehåller samma värde som den angivna strängen.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const String\& | Namnet att slå upp. |

### ReturnValue

Den atomiserade strängen eller **nullptr** om strängen ännu inte har atomiserats.

## Se även

* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
