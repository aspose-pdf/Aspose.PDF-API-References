---
title: "System::IO::Stream::EndRead метод"
linktitle: "EndRead"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::Stream::EndRead метод. Ожидает завершения указанной асинхронной операции чтения в C++."
type: docs
weight: 600
url: /ru/cpp/system.io/stream/endread/
---
## Stream::EndRead method


Ожидает завершения указанной асинхронной операции чтения.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<System::IAsyncResult\> | Объект [IAsyncResult](../../../system/iasyncresult/) представляющий асинхронную операцию чтения |

### ReturnValue

The number of bytes read during the read operation represented by **asyncResult**

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
