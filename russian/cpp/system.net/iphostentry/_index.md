---
title: "Класс System::Net::IPHostEntry"
linktitle: "IPHostEntry"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::IPHostEntry. Представляет информацию об интернет‑адресе хоста. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2600
url: /ru/cpp/system.net/iphostentry/
---
## IPHostEntry class


Представляет информацию об интернет‑адресе хоста. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class IPHostEntry : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AddressList](./get_addresslist/)() | Получает коллекцию IP‑адресов хоста. |
| [get_Aliases](./get_aliases/)() | Получает коллекцию псевдонимов хоста. |
| [get_HostName](./get_hostname/)() const | Информация RTTI. |
| [IPHostEntry](./iphostentry/)() | Создаёт новый экземпляр. |
| [set_AddressList](./set_addresslist/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>) | Устанавливает коллекцию IP‑адресов хоста. |
| [set_Aliases](./set_aliases/)(System::ArrayPtr\<String\>) | Устанавливает коллекцию псевдонимов хоста. |
| [set_HostName](./set_hostname/)(String) | Устанавливает имя хоста. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
