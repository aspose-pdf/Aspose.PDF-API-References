---
title: "System::Net::WebRequest::EndGetRequestStream метод"
linktitle: "EndGetRequestStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::WebRequest::EndGetRequestStream метод. Ожидает завершения указанной асинхронной операции получения потока в C++."
type: docs
weight: 1200
url: /ru/cpp/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream method


Ожидает завершения указанной асинхронной операции получения потока.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Объект [IAsyncResult](../../../system/iasyncresult/), представляющий асинхронную операцию получения потока. |

### ReturnValue

Поток для записи данных в ресурс.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
