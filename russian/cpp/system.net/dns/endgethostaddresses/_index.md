---
title: "System::Net::Dns::EndGetHostAddresses метод"
linktitle: "EndGetHostAddresses"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Dns::EndGetHostAddresses метод. Ожидает завершения указанной асинхронной операции по созданию нового экземпляра класса IPHostEntry в C++."
type: docs
weight: 500
url: /ru/cpp/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses method


Ожидает завершения указанной асинхронной операции по созданию нового экземпляра IPHostEntry-class.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Объект [IAsyncResult](../../../system/iasyncresult/) , представляющий асинхронную операцию. |

### ReturnValue

Новосозданный экземпляр класса IPHostEntry.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../ipaddress/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
