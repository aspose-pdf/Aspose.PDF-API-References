---
title: "Метод System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength"
linktitle: "GetRangeItemListLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength. Преобразует переданную строку, начиная с указанной позиции, в коллекцию экземпляров класса RangeItemHeaderValue в C++."
type: docs
weight: 800
url: /ru/cpp/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength method


Преобразует переданную строку, начиная с указанной позиции, в коллекцию экземпляров класса RangeItemHeaderValue.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | String | Строка для разбора. |
| startIndex | int32_t | Начальная позиция для разбора. |
| rangeCollection | System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\> | Экземпляр, в который будет присвоена разобранная коллекция. |

### ReturnValue

Длина разобранной подстроки, иначе 0.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [RangeItemHeaderValue](../)
* Class [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
