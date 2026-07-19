---
title: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength метод"
linktitle: "GetNameValueLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength метод. Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса NameValueHeaderValue на C++."
type: docs
weight: 900
url: /ru/cpp/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) method


Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | String | Строка для разбора. |
| startIndex | int32_t | Начальная позиция для разбора. |
| nameValueCreator | HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\> | Функция, используемая для создания новых экземпляров класса [NameValueHeaderValue](../). |
| parsedValue | System::SharedPtr\<NameValueHeaderValue\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### ReturnValue

Возвращает длину разобранной подстроки, иначе 0.

## См. также

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) method


Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | String | Строка для разбора. |
| startIndex | int32_t | Начальная позиция для разбора. |
| parsedValue | System::SharedPtr\<NameValueHeaderValue\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### ReturnValue

Возвращает длину разобранной подстроки, иначе 0.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
