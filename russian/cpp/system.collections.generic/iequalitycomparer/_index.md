---
title: "Класс System::Collections::Generic::IEqualityComparer"
linktitle: "IEqualityComparer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::IEqualityComparer. Интерфейс, предоставляющий возможность сравнивать два объекта на равенство. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2400
url: /ru/cpp/system.collections.generic/iequalitycomparer/
---
## IEqualityComparer class


Интерфейс, предоставляющий возможность сравнивать два объекта на равенство. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class IEqualityComparer : public virtual System::Object
```


| Параметр | Описание |
| --- | --- |
| T | Тип, который сравнивается. |
## Методы

| Метод | Описание |
| --- | --- |
| virtual [Equals](./equals/)(T, T) const | Информация RTTI. |
| virtual [GetHashCode](./gethashcode/)(T) const | Получает хеш-код для некоторого объекта. |

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
