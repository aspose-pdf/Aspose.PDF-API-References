---
title: "System::Xml::XmlNameTable::Get метод"
linktitle: "Get"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNameTable::Get метод. При переопределении в производном классе получает атомизированную строку, содержащую те же символы, что и указанный диапазон символов в данном массиве в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


При переопределении в производном классе возвращает атомизированную строку, содержащую те же символы, что и указанный диапазон символов в данном массиве.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const ArrayPtr\<char16_t\>\& | Массив символов, содержащий имя для поиска. |
| смещение | int32_t | Индекс в массиве, начинающийся с нуля, указывающий первый символ имени. |
| длина | int32_t | Количество символов в имени. |

### ReturnValue

Атомизированная строка или **nullptr**, если строка ещё не была атомизирована. Если **length** равен нулю, возвращается [String::Empty](../../../system/string/empty/).

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNameTable::Get(const String\&) method


При переопределении в производном классе возвращает атомизированную строку, содержащую то же значение, что и указанная строка.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const String\& | Имя для поиска. |

### ReturnValue

Атомизированная строка или **nullptr**, если строка ещё не была атомизирована.

## См. также

* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
