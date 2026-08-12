---
title: "System::Net::HttpWebRequest::EndGetRequestStream метод"
linktitle: "EndGetRequestStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::HttpWebRequest::EndGetRequestStream метод. Ожидает, пока указанная асинхронная операция получения потока не завершится в C++."
type: docs
weight: 600
url: /ru/cpp/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream method


Ожидает завершения указанной асинхронной операции получения потока.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
