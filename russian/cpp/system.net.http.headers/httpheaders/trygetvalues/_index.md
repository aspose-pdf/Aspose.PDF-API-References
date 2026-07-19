---
title: "System::Net::Http::Headers::HttpHeaders::TryGetValues метод"
linktitle: "TryGetValues"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::HttpHeaders::TryGetValues метод. Пытается получить соответствующие значения по указанному имени в C++."
type: docs
weight: 1900
url: /ru/cpp/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues method


Пытается получить соответствующие значения по указанному имени.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя заголовка. |
| значения | System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | Экземпляр, в котором будут присвоены соответствующие значения. |

### ReturnValue

Истина, если значения заголовка найдены по указанному имени, иначе ложь.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [HttpHeaders](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
