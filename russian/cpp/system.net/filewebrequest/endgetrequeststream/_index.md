---
title: "System::Net::FileWebRequest::EndGetRequestStream метод"
linktitle: "EndGetRequestStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::FileWebRequest::EndGetRequestStream метод. Ожидает завершения указанной асинхронной операции получения потока в C++."
type: docs
weight: 500
url: /ru/cpp/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream method


Ожидает завершения указанной асинхронной операции получения потока.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
