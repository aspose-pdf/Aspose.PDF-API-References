---
title: "System::Net::HttpWebRequest::BeginGetRequestStream метод"
linktitle: "BeginGetRequestStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::HttpWebRequest::BeginGetRequestStream метод. Инициирует асинхронную операцию получения потока для записи данных в ресурс в C++."
type: docs
weight: 400
url: /ru/cpp/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream method


Инициирует асинхронную операцию получения потока для записи данных в ресурс.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
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
