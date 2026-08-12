---
title: "System::ArraySegment class"
linktitle: "ArraySegment"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::ArraySegment class. Представляет сегмент одномерного массива. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 400
url: /ru/cpp/system/arraysegment/
---
## ArraySegment class


Представляет сегмент одномерного массива. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
template<typename T>class ArraySegment : public System::Object
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов сегмента массива. |
## Методы

| Метод | Описание |
| --- | --- |
| [ArraySegment](./arraysegment/)(System::ArrayPtr\<T\>) |  |
| [ArraySegment](./arraysegment/)(System::ArrayPtr\<T\>, int32_t, int32_t) |  |
| [ArraySegment](./arraysegment/)() |  |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(ArraySegment\<T\>) |  |
| [get_Array](./get_array/)() const |  |
| [get_Count](./get_count/)() const |  |
| [get_Offset](./get_offset/)() const |  |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../object/gethashcode/). Позволяет выполнять хеширование пользовательских объектов. |
| [operator[]](./operator[]/)(int32_t) const |  |
| [Slice](./slice/)(int32_t, int32_t) |  |
| [ToArray](./toarray/)() const |  |
## Примечания



```cpp
#include <system/array_segment.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<ArraySegment<String>> &segment)
{
  for (auto i = segment->get_Offset(); i < segment->get_Offset() + segment->get_Count(); i++)
  {
    std::cout << segment->get_Array()[i] << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Создайте и заполните массив.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // Создайте сегмент массива, содержащий весь массив.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // Выведите элементы сегмента массива.
  Print(fullArray);

  // Создайте сегмент массива.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // Выведите элементы сегмента массива.
  Print(segment);

  return 0;
}
/*
This code example produces the following output:
First Second Third
Second Third
*/
```

## См. также

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
