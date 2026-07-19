---
title: "Класс System::Net::IPEndPoint"
linktitle: "IPEndPoint"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::IPEndPoint. Представляет сетевую конечную точку, содержащую IP‑адрес и порт. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2500
url: /ru/cpp/system.net/ipendpoint/
---
## IPEndPoint class


Представляет сетевую конечную точку, содержащую IP‑адрес и порт. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class IPEndPoint : public System::Net::EndPoint
```

## Методы

| Метод | Описание |
| --- | --- |
| [Create](./create/)(System::SharedPtr\<SocketAddress\>) override | Создайте новый экземпляр класса [EndPoint](../endpoint/) с использованием указанного адреса сокета. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_Address](./get_address/)() | Получает адрес конечной точки. |
| [get_AddressFamily](./get_addressfamily/)() override | Информация RTTI. |
| [get_Port](./get_port/)() | Получает номер порта. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [GetImpl](./getimpl/)() const override | Возвращает указатель на реализацию. |
| [IPEndPoint](./ipendpoint/)(int64_t, int32_t) | Создаёт новый экземпляр. |
| [IPEndPoint](./ipendpoint/)(System::SharedPtr\<IPAddress\>, int32_t) | Создаёт новый экземпляр. |
| [set_Address](./set_address/)(System::SharedPtr\<IPAddress\>) | Устанавливает адрес конечной точки. |
| [set_Port](./set_port/)(int32_t) | Устанавливает номер порта. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Any](./any/) | Конечная точка для любого IPv4‑адреса и любого порта. |
| static [AnyPort](./anyport/) | Значение, указывающее, может ли использоваться любой порт. |
| static [IPv6Any](./ipv6any/) | Конечная точка для любого IPv6‑адреса и любого порта. |
| static [MaxPort](./maxport/) | Максимальный номер порта. |
| static [MinPort](./minport/) | Информация RTTI. |
## См. также

* Class [EndPoint](../endpoint/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
