---
title: "System::Net::Sockets::NetworkStream::EndRead method"
linktitle: "EndRead"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::NetworkStream::EndRead method. Ожидает завершения указанной асинхронной операции чтения в C++."
type: docs
weight: 600
url: /ru/cpp/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead method


Ожидает завершения указанной асинхронной операции чтения.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Объект [IAsyncResult](../../../system/iasyncresult/) представляющий асинхронную операцию чтения |

### ReturnValue

The number of bytes read during the read operation represented by **asyncResult**

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
