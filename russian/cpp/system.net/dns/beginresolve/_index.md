---
title: "Метод System::Net::Dns::BeginResolve"
linktitle: "BeginResolve"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::Dns::BeginResolve. Инициирует асинхронную операцию по созданию нового экземпляра класса IPHostEntry с использованием указанного имени хоста в C++."
type: docs
weight: 400
url: /ru/cpp/system.net/dns/beginresolve/
---
## Dns::BeginResolve method


Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-class, используя указанное имя хоста.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| hostName | String | Имя хоста, которое используется для создания нового экземпляра класса [IPHostEntry](../../iphostentry/). |
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
