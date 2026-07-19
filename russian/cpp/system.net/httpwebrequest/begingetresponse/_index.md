---
title: "Метод System::Net::HttpWebRequest::BeginGetResponse"
linktitle: "BeginGetResponse"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::HttpWebRequest::BeginGetResponse. Инициирует асинхронный запрос ресурса в C++."
type: docs
weight: 500
url: /ru/cpp/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse method


Инициирует асинхронный запрос к ресурсу.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| обратный вызов | AsyncCallback | Обратный вызов, который будет вызван после завершения операции. |
| state | System::SharedPtr\<Object\> | Данные, предоставленные пользователем, используемые для уникальной иденфикации каждой асинхронной операции. |

### ReturnValue

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
