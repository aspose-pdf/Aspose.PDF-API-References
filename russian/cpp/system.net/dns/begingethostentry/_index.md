---
title: "System::Net::Dns::BeginGetHostEntry метод"
linktitle: "BeginGetHostEntry"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Dns::BeginGetHostEntry метод. Инициирует асинхронную операцию по созданию нового экземпляра класса IPHostEntry с использованием указанной строки, содержащей имя хоста или IP‑адрес, в C++."
type: docs
weight: 300
url: /ru/cpp/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) method


Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-класса, используя указанную строку, содержащую имя хоста или IP‑адрес.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| hostNameOrAddress | String | Строка, содержащая имя хоста или IP‑адрес. |
| requestCallback | AsyncCallback | Обратный вызов, который будет вызван после завершения операции. |
| stateObject | System::SharedPtr\<Object\> | Данные, предоставленные пользователем, используемые для уникальной иденфикации каждой асинхронной операции. |

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
## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) method


Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-class, используя указанный IP‑адрес.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| адрес | System::SharedPtr\<IPAddress\> | IP‑адрес. |
| requestCallback | AsyncCallback | Обратный вызов, который будет вызван после завершения операции. |
| stateObject | System::SharedPtr\<Object\> | Данные, предоставленные пользователем, используемые для уникальной иденфикации каждой асинхронной операции. |

### ReturnValue

Объект [IAsyncResult](../../../system/iasyncresult/), представляющий инициированную асинхронную операцию.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [IPAddress](../../ipaddress/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
