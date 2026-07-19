---
title: "System::Net::Security::SslStream::EndRead метод"
linktitle: "EndRead"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Security::SslStream::EndRead метод. Ожидает завершения указанной асинхронной операции чтения в C++."
type: docs
weight: 700
url: /ru/cpp/system.net.security/sslstream/endread/
---
## SslStream::EndRead method


Ожидает завершения указанной асинхронной операции чтения.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Объект [IAsyncResult](../../../system/iasyncresult/) представляющий асинхронную операцию чтения |

### ReturnValue

The number of bytes read during the read operation represented by **asyncResult**

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
