---
title: "System::Net::Sockets::IPPacketInformation класс"
linktitle: "IPPacketInformation"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::IPPacketInformation class. Представляет информацию о пакете. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.net.sockets/ippacketinformation/
---
## IPPacketInformation class


Представляет информацию о пакете. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class IPPacketInformation : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает два объекта, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_Address](./get_address/)() | Возвращает адрес, откуда получен пакет. |
| [get_Interface](./get_interface/)() | Возвращает информацию о сетевом интерфейсе. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [IPPacketInformation](./ippacketinformation/)(System::SharedPtr\<IPAddress\>, int32_t) | Создаёт новый экземпляр. |
| [IPPacketInformation](./ippacketinformation/)() | Создаёт новый экземпляр. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
