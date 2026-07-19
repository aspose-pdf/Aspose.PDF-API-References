---
title: "System::Net::Http::Headers::HttpHeaders::ParsedValuesAsList метод"
linktitle: "ParsedValuesAsList"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::HttpHeaders::ParsedValuesAsList метод. Преобразует разобранные значения в список в C++."
type: docs
weight: 2100
url: /ru/cpp/system.net.http.headers/httpheaders/parsedvaluesaslist/
---
## HttpHeaders::ParsedValuesAsList method


Преобразует разобранные значения в список.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Object>>> System::Net::Http::Headers::HttpHeaders::ParsedValuesAsList(const System::SharedPtr<Object> parsedValues)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| parsedValues | const System::SharedPtr\<Object\> | Объект Values для преобразования. |

### ReturnValue

Если переданное значение является экземпляром List, возвращает его; в противном случае возвращает nullptr.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [Object](../../../system/object/)
* Class [HttpHeaders](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
