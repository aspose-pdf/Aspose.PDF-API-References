---
title: "Класс System::Collections::Generic::SortedDictionary::Enumerator"
linktitle: "Перечислитель"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::SortedDictionary::Enumerator class. Тип перечислителя для обхода словаря. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2100
url: /ru/cpp/system.collections.generic/sorteddictionary/enumerator/
---
## Enumerator class


[Enumerator](./) type to iterate through dictionary. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public System::Collections::Generic::SimpleEnumerator<map_t, KVPair>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Enumerator](./enumerator/)(const Ptr\&) | Создаёт перечислитель для конкретного словаря. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [EnumeratorType](./enumeratortype/) | Псевдоним типа [Enumerator](./). |
## См. также

* Class [SimpleEnumerator](../../simpleenumerator/)
* Class [SortedDictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
