---
title: "Метод System::Net::Dns::EndGetHostEntry"
linktitle: "EndGetHostEntry"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Dns::EndGetHostEntry метод. Ожидает завершения указанной асинхронной операции по созданию нового экземпляра класса IPHostEntry в C++."
type: docs
weight: 700
url: /ru/cpp/system.net/dns/endgethostentry/
---
## Dns::EndGetHostEntry method


Ожидает завершения указанной асинхронной операции по созданию нового экземпляра IPHostEntry-class.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostEntry(System::SharedPtr<IAsyncResult> asyncResult)
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
