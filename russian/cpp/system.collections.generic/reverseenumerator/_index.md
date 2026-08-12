---
title: "Класс System::Collections::Generic::ReverseEnumerator"
linktitle: "ReverseEnumerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::ReverseEnumerator. Перечислитель, который обходит контейнер в обратном порядке. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3800
url: /ru/cpp/system.collections.generic/reverseenumerator/
---
## ReverseEnumerator class


[Enumerator](../baseset/) that reverse-iterates through container. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Container,typename Element>class ReverseEnumerator : public System::Collections::Generic::IEnumerator<typename Container::value_type>
```


| Параметр | Описание |
| --- | --- |
| Контейнер | Контейнер для обхода. |
| Элемент | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_Current](./get_current/)() const override | Получает текущий элемент. |
| [IsValid](./isvalid/)() const | Проверяет, был ли вызван [MoveNext()](./movenext/) и конец не был достигнут. |
| [MoveNext](./movenext/)() override | Инкремент в стиле перечислителя. |
| [Reset](./reset/)() override | Сбрасывает перечислитель, позволяя повторно перечислять элементы. |
| [ReverseEnumerator](./reverseenumerator/)(const Object::ptr\&, Container\&) | Инициализирует итератор. |
| virtual [~ReverseEnumerator](./~reverseenumerator/)() | Деструктор. |

## См. также

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
