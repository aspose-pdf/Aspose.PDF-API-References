---
title: "Класс System::DefaultBoxedValue"
linktitle: "DefaultBoxedValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::DefaultBoxedValue. Реализация класса BoxedValue. Позволяет объявлять специализации BoxingValue без дублирования общего кода. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2100
url: /ru/cpp/system/defaultboxedvalue/
---
## DefaultBoxedValue class


[BoxedValue](../boxedvalue/) class implementation. Allows it BoxingValue specializations to be declared without duplicating common code. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | Создаёт новый экземпляр класса [DefaultBoxedValue](./), представляющий указанное значение. |
| [Equals](./equals/)(ptr) override | Определяет равенство упакованных значений, представленных текущим и указанным объектами. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш‑код для текущего объекта. |
| [GetType](./gettype/)() const override | Получает фактический тип объекта. |
| [is](./is/)() const | Определяет, является ли тип упакованного значения, представленного текущим объектом, **V**. |
| [ToString](./tostring/)() const override | Возвращает строковое представление упакованного значения. |
| [unbox](./unbox/)() const | Разупаковывает упакованное значение. |
## См. также

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
