---
title: "System::Xml::NameTable::Add metod"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::NameTable::Add metod. Atomiserar den angivna strängen och lägger till den i NameTable i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml/nametable/add/
---
## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Atomiserar den angivna strängen och lägger till den i [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | const ArrayPtr\<char16_t\>\& | Teckenarrayen som innehåller strängen att lägga till. |
| start | int32_t | Det nollbaserade indexet i arrayen som anger det första tecknet i strängen. |
| len | int32_t | Antalet tecken i strängen. |

### ReturnValue

Den atomiserade strängen eller den befintliga strängen om den redan finns i [NameTable](../). Om **len** är noll, returneras [String::Empty](../../../system/string/empty/).

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## NameTable::Add(const String\&) method


Atomiserar den angivna strängen och lägger till den i [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | const String\& | Strängen att lägga till. |

### ReturnValue

Den atomiserade strängen eller den befintliga strängen om den redan finns i [NameTable](../).

## Se även

* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
