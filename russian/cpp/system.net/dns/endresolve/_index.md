---
title: "Метод System::Net::Dns::EndResolve"
linktitle: "EndResolve"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::Dns::EndResolve. Ожидает завершения указанной асинхронной операции по созданию нового экземпляра класса IPHostEntry в C++."
type: docs
weight: 800
url: /ru/cpp/system.net/dns/endresolve/
---
## Dns::EndResolve method


Ожидает завершения указанной асинхронной операции по созданию нового экземпляра IPHostEntry-class.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndResolve(System::SharedPtr<IAsyncResult> asyncResult)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Объект [IAsyncResult](../../../system/iasyncresult/) , представляющий асинхронную операцию. |

### ReturnValue

Новосозданный экземпляр класса IPHostEntry.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
