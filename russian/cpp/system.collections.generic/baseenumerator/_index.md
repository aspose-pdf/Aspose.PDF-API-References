---
title: "Класс System::Collections::Generic::BaseEnumerator"
linktitle: "BaseEnumerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::BaseEnumerator. Определение перечислителя для обёртки типов в стиле STL для использования в стиле C#. Не делает предположений о структуре контейнера, за исключением наличия последовательного итератора. Использует функции begin() и end(). Экземпляры этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.collections.generic/baseenumerator/
---
## BaseEnumerator class


[Enumerator](../baseset/) definition to wrap STL-styled types for C#-styled usage. Makes no assertions on container structure except for existance of sequental iterator. Uses begin() and end() functions. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Container,typename Element>class BaseEnumerator : public System::Collections::Generic::IEnumerator<Element>
```


| Параметр | Описание |
| --- | --- |
| Контейнер | Тип контейнера в стиле STL. |
| Элемент | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [BaseEnumerator](./baseenumerator/)(const Object::ptr\&, Container\&) | Инициализирует итератор. |
| [IsValid](./isvalid/)() const | Проверяет, был ли вызван [MoveNext()](./movenext/) и конец не был достигнут. |
| [MoveNext](./movenext/)() override | Инкремент в стиле перечислителя. |
| [Reset](./reset/)() override | Сбрасывает перечислитель, позволяя повторно перечислять элементы. |

## См. также

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
