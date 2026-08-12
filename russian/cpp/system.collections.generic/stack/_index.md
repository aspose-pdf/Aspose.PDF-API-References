---
title: "Класс System::Collections::Generic::Stack"
linktitle: "Стек"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::Stack. Прямое объявление класса Stack в C++."
type: docs
weight: 4600
url: /ru/cpp/system.collections.generic/stack/
---
## Stack class


[Stack](./) class forward declaration.

```cpp
template<typename T>class Stack : public System::Collections::Generic::IEnumerable<T>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Методы

| Метод | Описание |
| --- | --- |
| [AddRange](./addrange/)(IEnumerablePtr) | Помещает элементы в стек. |
| virtual [Clear](./clear/)() | Удаляет все элементы из стека. |
| virtual [Contains](./contains/)(const T\&) const | Проверяет, присутствует ли конкретный элемент в контейнере; использует оператор == для сравнения. |
| [data](./data/)() | Внутренний аксессор структуры данных. |
| [data](./data/)() const | Внутренний аксессор структуры данных. |
| virtual [get_Count](./get_count/)() const | Получает количество элементов в стеке. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель для итерации по текущему стеку. |
| [Peek](./peek/)() | Получает элемент с вершины стека, но оставляет его в стеке. |
| [Pop](./pop/)() | Получает элемент с вершины стека. |
| [Push](./push/)(const T\&) | Помещает элемент на вершину стека. |
| [Stack](./stack/)() | Создаёт пустой стек. |
| [Stack](./stack/)(int) | Создаёт пустой стек. |
| [Stack](./stack/)(IEnumerablePtr) | Конструктор копирования. |
| virtual [ToArray](./toarray/)() | Преобразует стек в массив. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Коллекция, содержащая элементы одного типа. |
| [IEnumeratorPtr](./ienumeratorptr/) | Тип [Enumerator](./enumerator/). |
| [stack_t](./stack_t/) | Информация RTTI. |
| [ValueType](./valuetype/) | Тип значения. |
## Примечания


[Stack](./) class wrapping std::list. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/stack.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void PrintItems(const SmartPtr<IEnumerable<int>> &stack)
{
  for (const auto item: stack)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Создайте экземпляр класса Stack.
  auto stack = MakeObject<Stack<int>>();

  // Заполните стек.
  stack->Push(1);
  stack->Push(2);
  stack->Push(3);

  // Выведите последний элемент стека. Метод Peek не удаляет элемент из стека.
  std::cout << stack->Peek() << std::endl;
  PrintItems(stack);

  // Выведите последний элемент стека. Метод Pop удаляет элемент из стека.
  std::cout << stack->Pop() << std::endl;
  PrintItems(stack);

  return 0;
}
/*
This code example produces the following output:
3
3 2 1
3
2 1
*/
```

## См. также

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
