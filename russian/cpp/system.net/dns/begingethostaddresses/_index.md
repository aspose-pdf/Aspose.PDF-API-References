---
title: "System::Net::Dns::BeginGetHostAddresses метод"
linktitle: "BeginGetHostAddresses"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Dns::BeginGetHostAddresses метод. Инициирует асинхронную операцию по созданию нового экземпляра класса IPHostEntry с использованием указанной строки, содержащей имя хоста или IP‑адрес, в C++."
type: docs
weight: 100
url: /ru/cpp/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses method


Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-класса, используя указанную строку, содержащую имя хоста или IP‑адрес.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| hostNameOrAddress | String | Строка, содержащая имя хоста или IP‑адрес. |
| requestCallback | AsyncCallback | Обратный вызов, который будет вызван после завершения операции. |
| state | System::SharedPtr\<Object\> | Данные, предоставленные пользователем, используемые для уникальной иденфикации каждой асинхронной операции. |

### ReturnValue

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
