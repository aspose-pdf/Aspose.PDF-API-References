---
title: "Класс System::Collections::Generic::SimpleEnumerator"
linktitle: "SimpleEnumerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::SimpleEnumerator. Класс‑итератор для простых контейнеров, хранящих элементы напрямую с использованием функций rbegin() и rend(). Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3900
url: /ru/cpp/system.collections.generic/simpleenumerator/
---
## SimpleEnumerator class


Класс‑итератор для простых контейнеров, хранящих элементы напрямую с использованием функций rbegin() и rend(). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename Container,typename Element>class SimpleEnumerator : public System::Collections::Generic::BaseEnumerator<Container, typename Container::value_type>
```


| Параметр | Описание |
| --- | --- |
| Контейнер | Тип контейнера для итерации. |
| Элемент | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Клонирует текущий итератор. |
| [get_Current](./get_current/)() const override | Получает текущий элемент. |
| [SimpleEnumerator](./simpleenumerator/)(Object::ptr, Container\&) | Создаёт простой итератор. |

## См. также

* Class [BaseEnumerator](../baseenumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
