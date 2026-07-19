---
title: "System::Net::WebRequest::BeginGetRequestStream метод"
linktitle: "BeginGetRequestStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::WebRequest::BeginGetRequestStream метод. Инициирует асинхронную операцию получения потока для записи данных в ресурс на C++."
type: docs
weight: 1000
url: /ru/cpp/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream method


Инициирует асинхронную операцию получения потока для записи данных в ресурс.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
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
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
