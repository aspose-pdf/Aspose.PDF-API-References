---
title: "System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength метод"
linktitle: "GetCacheControlLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength метод. Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса CacheControlHeaderValue на C++."
type: docs
weight: 3400
url: /ru/cpp/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength method


Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | String | Строка для разбора. |
| startIndex | int32_t | Начальная позиция для разбора. |
| storeValue | System::SharedPtr\<CacheControlHeaderValue\> | Значение, которое должно быть добавлено к разобранному объекту. |
| parsedValue | System::SharedPtr\<CacheControlHeaderValue\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### ReturnValue

Длина разобранной подстроки, иначе 0.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CacheControlHeaderValue](../)
* Class [CacheControlHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
