---
title: "System::Collections::Generic::IEnumerator класс"
linktitle: "IEnumerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::IEnumerator класс. Интерфейс перечислителя, который можно использовать для итерации по некоторым элементам. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2300
url: /ru/cpp/system.collections.generic/ienumerator/
---
## IEnumerator class


Интерфейс перечислителя, который можно использовать для перебора некоторых элементов. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class IEnumerator : public virtual System::IDisposable,
                                        public System::Details::EnumeratorBasedIterator<T>,
                                        protected System::Details::IteratorPointerUpdater<T, false>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [AsVirtualizedIterator](./asvirtualizediterator/)() | Подготавливает итератор для использования классом VirtualizedIterator. |
| [CloneIterator](./cloneiterator/)() const override | Клонирует текущий итератор. |
| virtual [Current](./current/)() const | Получает текущий элемент. |
| virtual [get_Current](./get_current/)() const | Получает текущий элемент. |
| [IEnumerator](./ienumerator/)() |  |
| [IncrementIterator](./incrementiterator/)() override | Перемещает итератор на шаг вперёд. |
| [InitializeIterator](./initializeiterator/)() override | Выполняет первый вызов [MoveNext()](./movenext/) и подготавливает объект перечислителя для использования VirtualizedIterator. |
| [MarkOwnedByVirtualizedIterator](./markownedbyvirtualizediterator/)() | Помечает перечислитель, принадлежащий виртуализированному итератору. |
| virtual [MoveNext](./movenext/)() | Перемещает перечислитель к следующему элементу. Если ранее ни один элемент не был выбран, устанавливает ссылку на первый доступный элемент. Если достигнут конец контейнера, ничего не делает. |
| virtual [Reset](./reset/)() | Сбрасывает перечислитель в позицию перед первым элементом. |
| virtual [~IEnumerator](./~ienumerator/)() |  |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [ValueType](./valuetype/) | Тип значения. |
## Примечания



```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Создайте экземпляр класса List.
  auto collection = MakeObject<List<int>>();

  // Заполните список.
  collection->Add(1);
  collection->Add(2);
  collection->Add(3);

  // Получите перечислитель списка.
  auto enumerator = collection->GetEnumerator();

  while (enumerator->MoveNext())
  {
    // Получите текущий элемент и выведите его.
    std::cout << enumerator->get_Current() << ' ';
  }

  // Сбросьте перечислитель.
  enumerator->Reset();

  return 0;
}
/*
This code example produces the following output:
1 2 3
*/
```

## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
