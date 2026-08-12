---
title: "Класс System::Net::IPAddress"
linktitle: "IPAddress"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::IPAddress. Представляет IP‑адрес. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2400
url: /ru/cpp/system.net/ipaddress/
---
## IPAddress class


Представляет IP‑адрес. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class IPAddress : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_AddressFamily](./get_addressfamily/)() | Возвращает семейство адресов. |
| [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Возвращает значение, указывающее, является ли адрес IPv4‑адресом и отображён ли он в IPv6‑адрес. |
| [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Возвращает значение, указывающее, является ли адрес локальным адресом IPv6 link-local. |
| [get_IsIPv6Multicast](./get_isipv6multicast/)() | Возвращает значение, указывающее, является ли адрес глобальным мультикаст‑адресом IPv6. |
| [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Возвращает значение, указывающее, является ли адрес IPv6 site-local адресом. |
| [get_IsIPv6Teredo](./get_isipv6teredo/)() | Возвращает значение, указывающее, является ли адрес IPv6 Teredo адресом. |
| [get_ScopeId](./get_scopeid/)() | Получает идентификатор области IPv6-адреса. |
| [GetAddressBytes](./getaddressbytes/)() | Возвращает массив байтов IP-адреса. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [GetImpl](./getimpl/)() const | Возвращает указатель на реализацию. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int64_t) | Преобразует указанный порядок байтов хоста в соответствующий порядок байтов сети. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int32_t) | Преобразует указанный порядок байтов хоста в соответствующий порядок байтов сети. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int16_t) | Преобразует указанный порядок байтов хоста в соответствующий порядок байтов сети. |
| [IPAddress](./ipaddress/)(int64_t) | Создаёт новый экземпляр. |
| [IPAddress](./ipaddress/)(System::ArrayPtr\<uint8_t\>, int64_t) | Создаёт новый экземпляр. |
| [IPAddress](./ipaddress/)(System::ArrayPtr\<uint8_t\>) | Создаёт новый экземпляр. |
| [IPAddress](./ipaddress/)() | Создаёт новый экземпляр. |
| static [IsLoopback](./isloopback/)(System::SharedPtr\<IPAddress\>) | Возвращает значение, указывающее, является ли указанный адрес loopback-адресом. |
| [MapToIPv4](./maptoipv4/)() | Преобразует адрес в IPv4-адрес. |
| [MapToIPv6](./maptoipv6/)() | Преобразует адрес в IPv6-адрес. |
| static [NetworkToHostOrder](./networktohostorder/)(int64_t) | Преобразует указанный порядок байтов сети в соответствующий порядок байтов хоста. |
| static [NetworkToHostOrder](./networktohostorder/)(int32_t) | Преобразует указанный порядок байтов сети в соответствующий порядок байтов хоста. |
| static [NetworkToHostOrder](./networktohostorder/)(int16_t) | Преобразует указанный порядок байтов сети в соответствующий порядок байтов хоста. |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [IPAddress](./). |
| [set_ScopeId](./set_scopeid/)(int64_t) | Устанавливает идентификатор области IPv6-адреса. |
| [SetImpl](./setimpl/)(ImplPtr) | Устанавливает указатель на реализацию. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<IPAddress\>\&) | Пытается преобразовать переданную строку в экземпляр класса [IPAddress](./). |
## Поля

| Поле | Описание |
| --- | --- |
| static [Any](./any/) | Информация RTTI. |
| static [Broadcast](./broadcast/) | IPv4 широковещательный адрес. |
| static [IPv6Any](./ipv6any/) | IPv6-адрес, указывающий, должен ли сервер прослушивать все сетевые интерфейсы. |
| static [IPv6Loopback](./ipv6loopback/) | IPv6 loopback-адрес. |
| static [IPv6None](./ipv6none/) | IPv6-адрес, указывающий, не должен ли сервер прослушивать какой-либо сетевой интерфейс. |
| static [Loopback](./loopback/) | IPv4 loopback-адрес. |
| static [None](./none/) | IPv4-адрес, указывающий, не должен ли сервер прослушивать какой-либо сетевой интерфейс. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [ImplPtr](./implptr/) | Указатель на тип реализации. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
