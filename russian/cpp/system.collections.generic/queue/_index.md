---
title: "Класс System::Collections::Generic::Queue"
linktitle: "Queue"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::Queue. Предварительное объявление класса Queue в C++."
type: docs
weight: 3600
url: /ru/cpp/system.collections.generic/queue/
---
## Queue class


[Queue](./) class forward declaration.

```cpp
template<typename T>class Queue : public System::Collections::Generic::IEnumerable<T>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Методы

| Метод | Описание |
| --- | --- |
| virtual [Clear](./clear/)() | Удаляет все элементы в очереди. |
| virtual [Contains](./contains/)(const T\&) const | Проверяет, содержит ли очередь конкретный элемент, используя оператор == для сравнения элементов. |
| [data](./data/)() | Доступ к базовой структуре данных. |
| [data](./data/)() const | Доступ к базовой структуре данных. |
| [Dequeue](./dequeue/)() | Получает элемент из начала очереди. |
| [Enqueue](./enqueue/)(const T\&) | Помещает элемент в конец очереди. |
| virtual [get_Count](./get_count/)() const | Получает количество элементов в очереди. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель для итерации по очереди. |
| [Peek](./peek/)() | Получает элемент из начала очереди, но не удаляет его из очереди. |
| [Queue](./queue/)() | Создаёт пустую очередь. |
| [Queue](./queue/)(int) | Создаёт пустую очередь. |
| [Queue](./queue/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Конструктор копирования. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Контейнер элементов одного типа. |
| [IEnumeratorPtr](./ienumeratorptr/) | Тип [Enumerator](./enumerator/). |
| [queue_t](./queue_t/) | Информация RTTI. |
| [ValueType](./valuetype/) | Этот тип. |
## Примечания


[Queue](./) container wrapping STL list. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/queue.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void PrintItems(const SmartPtr<IEnumerable<int>> &queue)
{
  for (const int item: queue)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Создайте экземпляр класса Queue.
  auto queue = MakeObject<Queue<int>>();

  // Заполните очередь.
  queue->Enqueue(1);
  queue->Enqueue(2);
  queue->Enqueue(3);

  // Выведите первый элемент очереди. Метод Peek не удаляет элемент из очереди.
  std::cout << queue->Peek() << std::endl;
  // Выведите элементы очереди.
  PrintItems(queue);

  // Выведите первый элемент очереди. Метод Dequeue удаляет элемент из очереди.
  std::cout << queue->Dequeue() << std::endl;
  // Выведите элементы очереди.
  PrintItems(queue);

  return 0;
}
/*
This code example produces the following output:
1
1 2 3
1
2 3
*/
```

## См. также

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
