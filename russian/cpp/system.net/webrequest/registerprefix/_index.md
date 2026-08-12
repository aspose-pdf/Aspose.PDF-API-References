---
title: "System::Net::WebRequest::RegisterPrefix метод"
linktitle: "RegisterPrefix"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::WebRequest::RegisterPrefix метод. Регистрирует наследник WebRequest для указанного URI в C++."
type: docs
weight: 600
url: /ru/cpp/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix method


Регистрирует наследник [WebRequest](../) для указанного URI.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | String | URI или префикс URI. |
| creator | System::SharedPtr\<IWebRequestCreate\> | Создаёт новые экземпляры класса [WebRequest](../). |

### ReturnValue

True, когда наследник [WebRequest](../) успешно зарегистрирован для указанного URI, иначе false.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWebRequestCreate](../../iwebrequestcreate/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
