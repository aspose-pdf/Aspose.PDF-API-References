---
title: "System::Net::NetworkInformation::IPGlobalProperties класс"
linktitle: "IPGlobalProperties"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::NetworkInformation::IPGlobalProperties класс. Представляет информацию о сетевом соединении локального компьютера. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.net.networkinformation/ipglobalproperties/
---
## IPGlobalProperties class


Представляет информацию о сетевом соединении локального компьютера. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class IPGlobalProperties : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_DomainName](./get_domainname/)() | Возвращает домен, в котором зарегистрирован локальный компьютер. |
| virtual [get_HostName](./get_hostname/)() | Возвращает имя хоста локального компьютера. |
| static [GetIPGlobalProperties](./getipglobalproperties/)() | Информация RTTI. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net::NetworkInformation](../)
* Library [Aspose.PDF for C++](../../)
