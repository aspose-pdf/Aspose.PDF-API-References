---
title: "Класс System::Array::Enumerator"
linktitle: "Перечислитель"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Array::Enumerator. Реализует интерфейс IEnumerator, который позволяет перечислять элементы объекта Array. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 7000
url: /ru/cpp/system/array/enumerator/
---
## Enumerator class


Реализует интерфейс IEnumerator, который позволяет перечислять элементы объекта [Array](../) . Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Enumerator : public virtual System::Object,
                   public System::Collections::Generic::IEnumerator<T>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Enumerator](./enumerator/)(const SharedPtr\<Array\<T\>\>\&) | Создаёт новый объект [Enumerator](./) , представляющий указанный массив. |
| [get_Current](./get_current/)() const override | Возвращает копию текущего элемента. |
| [MoveNext](./movenext/)() override | Проверяет, указывает ли индекс текущего элемента не на последний элемент в массиве, и продвигает его, если это не так. |
| [Reset](./reset/)() override | Сбрасывает индекс текущего элемента. |
| virtual [~Enumerator](./~enumerator/)() | Деструктор. |
## См. также

* Class [Object](../../object/)
* Class [IEnumerator](../../../system.collections.generic/ienumerator/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
