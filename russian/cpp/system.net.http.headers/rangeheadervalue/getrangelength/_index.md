---
title: "System::Net::Http::Headers::RangeHeaderValue::GetRangeLength метод"
linktitle: "GetRangeLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::RangeHeaderValue::GetRangeLength метод. Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса RangeHeaderValue на C++."
type: docs
weight: 800
url: /ru/cpp/system.net.http.headers/rangeheadervalue/getrangelength/
---
## RangeHeaderValue::GetRangeLength method


Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [RangeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeHeaderValue::GetRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | String | Строка для разбора. |
| startIndex | int32_t | Начальная позиция для разбора. |
| parsedValue | System::SharedPtr\<Object\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### ReturnValue

Возвращает длину разобранной подстроки, иначе 0.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RangeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
