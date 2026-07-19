---
title: "Класс System::Net::SocketAddress"
linktitle: "SocketAddress"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::SocketAddress. Используется для хранения сериализованной информации о экземплярах класса EndPoint. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3300
url: /ru/cpp/system.net/socketaddress/
---
## SocketAddress class


Используется для хранения сериализованной информации о экземплярах класса [EndPoint](../endpoint/). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SocketAddress : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_Family](./get_family/)() | Информация RTTI. |
| [get_Size](./get_size/)() | Возвращает размер базового буфера. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [idx_get](./idx_get/)(int32_t) | Получает значение базового буфера по указанному индексу. |
| [idx_set](./idx_set/)(int32_t, uint8_t) | Устанавливает значение базового буфера по указанному индексу. |
| [SocketAddress](./socketaddress/)(Sockets::AddressFamily) | Создаёт новый экземпляр. |
| [SocketAddress](./socketaddress/)(Sockets::AddressFamily, int32_t) | Создаёт новый экземпляр. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
