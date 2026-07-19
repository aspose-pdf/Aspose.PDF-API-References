---
title: "Метод System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength"
linktitle: "GetEntityTagLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength. Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса EntityTagHeaderValue в C++."
type: docs
weight: 800
url: /ru/cpp/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength method


Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | String | Строка для разбора. |
| startIndex | int32_t | Начальная позиция для разбора. |
| parsedValue | System::SharedPtr\\<EntityTagHeaderValue\\>\\& | Экземпляр, в который будет присвоен разобранный объект. |

### ReturnValue

Длина разобранной подстроки, иначе 0.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EntityTagHeaderValue](../)
* Class [EntityTagHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
