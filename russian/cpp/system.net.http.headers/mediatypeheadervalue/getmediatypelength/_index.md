---
title: "System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength метод"
linktitle: "GetMediaTypeLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength метод. Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса MediaTypeHeaderValue в C++."
type: docs
weight: 1000
url: /ru/cpp/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength method


Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | String | Строка для разбора. |
| startIndex | int32_t | Начальная позиция для разбора. |
| mediaTypeCreator | HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\> | Делегат, используемый для создания экземпляров класса [MediaTypeHeaderValue](../). |
| parsedValue | System::SharedPtr\<MediaTypeHeaderValue\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### ReturnValue

Возвращает длину разобранной подстроки, иначе 0.

## См. также

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MediaTypeHeaderValue](../)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
