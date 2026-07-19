---
title: "Класс System::Comparison"
linktitle: "Comparison"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Comparison. Представляет указатель на метод, который сравнивает два объекта одного типа. Этот тип должен быть выделен в стеке и передан функциям по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 1400
url: /ru/cpp/system/comparison/
---
## Comparison class


Представляет указатель на метод, который сравнивает два объекта одного типа. Этот тип должен быть выделен в стеке и передан функциям по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```


| Параметр | Описание |
| --- | --- |
| T | Тип объектов, которые сравнивает метод |
## Методы

| Метод | Описание |
| --- | --- |
| [operator()](./operator()/)(T, T) | Вызывает вызываемый объект, на который указывает текущий объект. |
## Примечания



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// Шаблонный класс, представляющий динамический массив.
template <typename T>
class MyArray
{
  // Используется для хранения данных массива.
  std::vector<T> m_data;

public:
  // Создаёт новый экземпляр нашего динамического массива.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Используется для сортировки данных массива. Этот метод принимает экземпляр
  // 'System::Comparison' шаблонный класс.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Возвращает количество элементов, которые хранит наш динамический массив.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Используется для получения элемента по указанному индексу.
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // Создайте экземпляр класса MyArray с указанными элементами.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Сортировать элементы динамического массива по возрастанию.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Вывести элементы динамического массива.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
This code example produces the following output:
a
b
c
d
e
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
