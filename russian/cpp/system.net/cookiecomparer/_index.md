---
title: "класс System::Net::CookieComparer"
linktitle: "CookieComparer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::CookieComparer. Используется для сравнения экземпляров класса Cookie. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.net/cookiecomparer/
---
## CookieComparer class


Используется для сравнения экземпляров класса [Cookie](../cookie/). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CookieComparer : public System::Collections::Generic::IComparer<System::SharedPtr<System::Net::Cookie>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Compare](./compare/)(args_type, args_type) const override | Сравнивает указанные объекты. |
| static [get_Instance](./get_instance/)() | Информация RTTI. |
## См. также

* Class [IComparer](../../system.collections.generic/icomparer/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
