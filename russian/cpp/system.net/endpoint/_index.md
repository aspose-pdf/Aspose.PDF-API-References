---
title: "Класс System::Net::EndPoint"
linktitle: "EndPoint"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::EndPoint. Абстрактный класс, содержащий сетевой адрес. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 900
url: /ru/cpp/system.net/endpoint/
---
## EndPoint class


Абстрактный класс, содержащий сетевой адрес. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class EndPoint : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Create](./create/)(System::SharedPtr\<SocketAddress\>) | Создайте новый экземпляр класса [EndPoint](./), используя указанный адрес сокета. |
| virtual [get_AddressFamily](./get_addressfamily/)() | Информация RTTI. |
| virtual [GetImpl](./getimpl/)() const | Возвращает указатель на реализацию. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [ImplPtr](./implptr/) | Указатель на реализацию. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
