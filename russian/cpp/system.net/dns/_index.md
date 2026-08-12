---
title: "System::Net::Dns класс"
linktitle: "Dns"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Dns класс. Предоставляет методы для работы с DNS в C++."
type: docs
weight: 700
url: /ru/cpp/system.net/dns/
---
## Dns class


Предоставляет методы для работы с DNS.

```cpp
class Dns : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [BeginGetHostAddresses](./begingethostaddresses/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-класса, используя указанную строку, содержащую имя хоста или IP‑адрес. |
| static [BeginGetHostByName](./begingethostbyname/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-class, используя указанное имя хоста. |
| static [BeginGetHostEntry](./begingethostentry/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-класса, используя указанную строку, содержащую имя хоста или IP‑адрес. |
| static [BeginGetHostEntry](./begingethostentry/)(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-class, используя указанный IP‑адрес. |
| static [BeginResolve](./beginresolve/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию по созданию нового экземпляра IPHostEntry-class, используя указанное имя хоста. |
| [Dns](./dns/)() | Удалённый конструктор по умолчанию. |
| static [EndGetHostAddresses](./endgethostaddresses/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции по созданию нового экземпляра IPHostEntry-class. |
| static [EndGetHostByName](./endgethostbyname/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции по созданию нового экземпляра IPHostEntry-class. |
| static [EndGetHostEntry](./endgethostentry/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции по созданию нового экземпляра IPHostEntry-class. |
| static [EndResolve](./endresolve/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции по созданию нового экземпляра IPHostEntry-class. |
| static [GetHostAddresses](./gethostaddresses/)(String) | Возвращает коллекцию IP‑адресов указанного имени хоста или IP‑адреса. |
| static [GetHostByAddress](./gethostbyaddress/)(String) | Создаёт новый экземпляр IPHostEntry-class, используя указанное строковое представление IP‑адреса. |
| static [GetHostByAddress](./gethostbyaddress/)(System::SharedPtr\<IPAddress\>) | Создаёт новый экземпляр IPHostEntry-class, используя указанный IP‑адрес. |
| static [GetHostByName](./gethostbyname/)(String) | Информация RTTI. |
| static [GetHostEntry](./gethostentry/)(String) | Создаёт новый экземпляр IPHostEntry-class, используя указанную строку, содержащую имя хоста или IP‑адрес. |
| static [GetHostEntry](./gethostentry/)(System::SharedPtr\<IPAddress\>) | Создаёт новый экземпляр IPHostEntry-class, используя указанный IP‑адрес. |
| static [GetHostName](./gethostname/)() | Возвращает имя хоста локального компьютера. |
| static [Resolve](./resolve/)(String) | Создаёт новый экземпляр IPHostEntry-class, используя указанное имя хоста. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
