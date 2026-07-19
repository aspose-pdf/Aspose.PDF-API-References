---
title: "Метод System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength"
linktitle: "GetRangeItemLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength. Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса RangeItemHeaderValue в C++."
type: docs
weight: 700
url: /ru/cpp/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength method


Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [RangeItemHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | String | Строка для разбора. |
| startIndex | int32_t | Начальная позиция для разбора. |
| parsedValue | System::SharedPtr\<RangeItemHeaderValue\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### ReturnValue

Возвращает длину разобранной подстроки, иначе 0.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RangeItemHeaderValue](../)
* Class [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
