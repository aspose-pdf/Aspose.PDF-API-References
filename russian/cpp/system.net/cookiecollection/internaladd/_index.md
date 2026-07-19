---
title: "System::Net::CookieCollection::InternalAdd метод"
linktitle: "InternalAdd"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::CookieCollection::InternalAdd. Добавляет указанную cookie в коллекцию в C++."
type: docs
weight: 1000
url: /ru/cpp/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd method


Добавляет указанный файл cookie в коллекцию.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| cookie | System::SharedPtr\<Cookie\> | Cookie для добавления. |
| isStrict | bool | True, когда указанная cookie должна заменить старую, иначе false. |

### ReturnValue

0, когда указанная cookie заменила старую, иначе 1.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
