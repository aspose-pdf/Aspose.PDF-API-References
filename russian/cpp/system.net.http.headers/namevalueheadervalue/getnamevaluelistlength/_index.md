---
title: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength метод"
linktitle: "GetNameValueListLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength метод. Преобразует переданную строку, начиная с указанного индекса, в коллекцию экземпляров класса NameValueHeaderValue и возвращает длину разобранной подстроки на C++."
type: docs
weight: 1000
url: /ru/cpp/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength method


Преобразует переданную строку, начиная с указанного индекса, в коллекцию экземпляров класса NameValueHeaderValue и возвращает длину разобранной подстроки.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | String | Строка для анализа. |
| startIndex | int32_t | Начальная позиция для анализа. |
| delimiter | char16_t | Строка, используемая для разделения элементов в указанной строке. |
| nameValueCollection | System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\> | Выходной параметр, в который будет присвоена разобранная коллекция. |

### ReturnValue

Длина разобранной подстроки.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
