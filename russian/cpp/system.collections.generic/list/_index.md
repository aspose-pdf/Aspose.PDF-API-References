---
title: "Класс System::Collections::Generic::List"
linktitle: "List"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::List. Предварительное объявление List в C++."
type: docs
weight: 3300
url: /ru/cpp/system.collections.generic/list/
---
## List class


[List](./) forward declaration.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Методы

| Метод | Описание |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<T\>) | Специфично для C++. |
| [Add](./add/)(const T\&) override | Добавляет элемент в конец списка. |
| [AddInitializer](./addinitializer/)(int, const T *) | Добавляет элементы в список; используется при переводе инициализаторов. |
| [AddRange](./addrange/)(IEnumerablePtr) | Добавляет все элементы из коллекции (или из неё самой) в конец текущего списка. |
| [AsReadOnly](./asreadonly/)() | Получает только для чтения ссылку на эту коллекцию. |
| [begin](./begin/)() | Возвращает итератор на первый элемент коллекции. |
| [begin](./begin/)() const | Получает итератор к первому элементу константно‑квалифицированной коллекции. |
| [BinarySearch](./binarysearch/)(const T\&) const | Ищет элемент в отсортированном списке. |
| [BinarySearch](./binarysearch/)(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const | Ищет элемент в отсортированном списке. |
| [BinarySearch](./binarysearch/)(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const | Ищет элемент в отсортированном списке. |
| [cbegin](./cbegin/)() const | Получает итератор к первому константно‑квалифицированному элементу коллекции. |
| [cend](./cend/)() const | Получает итератор для несуществующего константно‑квалифицированного элемента за концом коллекции. |
| [Clear](./clear/)() override | Удаляет все элементы. |
| [Contains](./contains/)(const T\&) const override | Проверяет, присутствует ли элемент в списке. |
| [ConvertAll](./convertall/)(Converter\<T, OutputType\>) | Создаёт список элементов, преобразованных в другой тип. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) override | Копирует элементы списка в существующие элементы массива. |
| [CopyTo](./copyto/)(const System::ArrayPtr\<T\>\&) | Копирует все элементы в существующие элементы массива. |
| [CopyTo](./copyto/)(int, const System::ArrayPtr\<T\>\&, int, int) | Копирует элементы, начиная с указанного индекса, в существующие элементы массива. |
| [crbegin](./crbegin/)() const | Получает обратный итератор к последнему элементу коллекции, квалифицированному как const (первый в обратном порядке). |
| [crend](./crend/)() const | Получает обратный итератор для несуществующего const‑квалифицированного элемента перед началом коллекции. |
| [data](./data/)() | Функция доступа к базовой структуре данных. |
| [data](./data/)() const | Функция доступа к базовой структуре данных. |
| [end](./end/)() | Получает итератор для несуществующего элемента за концом коллекции. |
| [end](./end/)() const | Получает итератор для несуществующего элемента за концом константно‑квалифицированной коллекции. |
| [Exists](./exists/)(System::Predicate\<T\>) | Проверяет, существует ли элемент, соответствующий заданному предикату, в списке. |
| [Find](./find/)(System::Predicate\<T\>) | Ищет элемент, соответствующий заданному предикату. |
| [FindAll](./findall/)(System::Predicate\<T\>) | Ищет элементы, соответствующие заданному предикату. |
| [FindIndex](./findindex/)(System::Predicate\<T\>) | Ищет элемент, соответствующий заданному предикату. |
| [FindIndex](./findindex/)(int, System::Predicate\<T\>) | Ищет элемент, соответствующий заданному предикату. |
| [FindIndex](./findindex/)(int, int, System::Predicate\<T\>) | Ищет элемент, соответствующий заданному предикату. |
| [FindLast](./findlast/)(System::Predicate\<T\>) | Ищет последний элемент, соответствующий заданному предикату. |
| [ForEach](./foreach/)(System::Action\<T\>) | Применяет действие ко всем элементам списка. |
| [get_Capacity](./get_capacity/)() const | Получает текущую ёмкость списка. |
| [get_Count](./get_count/)() const override | Получает количество элементов в текущем списке. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель для перебора элементов списка. |
| [GetRange](./getrange/)(int, int) | Создаёт срез списка. |
| [idx_get](./idx_get/)(int) const override | Получает элемент в определённой позиции. |
| [idx_set](./idx_set/)(int, T) override | Устанавливает элемент в определённой позиции. |
| [IndexOf](./indexof/)(const T\&) const override | Получает первый индекс указанного элемента. |
| [IndexOf](./indexof/)(const T\&, int) const | Ищет указанный элемент в списке. |
| [Insert](./insert/)(int, const T\&) override | Вставляет элемент в указанную позицию. |
| [InsertRange](./insertrange/)(int, IEnumerablePtr) | Вставляет диапазон данных в определённую позицию. |
| [LastIndexOf](./lastindexof/)(const T\&) const | Ищет указанный объект и возвращает нулевой индекс последнего вхождения во всём списке. |
| [LastIndexOf](./lastindexof/)(const T\&, int32_t) const | Ищет указанный объект и возвращает нулевой индекс последнего вхождения в диапазоне элементов [List](./), который простирается от первого элемента до указанного индекса. |
| [LastIndexOf](./lastindexof/)(const T\&, int32_t, int32_t) const | Ищет указанный объект и возвращает нулевой индекс последнего вхождения в диапазоне элементов [List](./), который содержит указанное количество элементов и заканчивается на указанном индексе. |
| [List](./list/)() | Создаёт пустой список. |
| [List](./list/)(int) | Создаёт список с заранее определённой ёмкостью. |
| [List](./list/)(IEnumerablePtr) | Конструктор копирования. |
| [operator[]](./operator[]/)(int) | Функция доступа. |
| [operator[]](./operator[]/)(int) const | Функция доступа. |
| [rbegin](./rbegin/)() | Получает обратный итератор к последнему элементу коллекции (первый в обратном порядке). |
| [rbegin](./rbegin/)() const | Получает обратный итератор к последнему элементу const‑квалифицированной коллекции (первый в обратном порядке). |
| [Remove](./remove/)(const T\&) override | Удаляет первое вхождение конкретного элемента из списка. |
| [RemoveAll](./removeall/)(Predicate\<T\>) | Удаляет все элементы, соответствующие заданному предикату. |
| [RemoveAt](./removeat/)(int) override | Удаляет элемент в указанной позиции. |
| [RemoveRange](./removerange/)(int, int) | Удаляет срез списка. |
| [rend](./rend/)() | Получает обратный итератор для несуществующего элемента перед началом коллекции. |
| [rend](./rend/)() const | Получает обратный итератор для несуществующего элемента перед началом const‑квалифицированной коллекции. |
| [Reverse](./reverse/)() | Изменяет порядок элементов всего списка на обратный. |
| [Reverse](./reverse/)(int, int) | Изменяет порядок элементов среза списка на обратный. |
| [set_Capacity](./set_capacity/)(int) | Устанавливает ёмкость списка. |
| [Sort](./sort/)(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) | Сортирует элементы в списке. |
| [Sort](./sort/)() | Сортирует элементы в списке, используя компаратор по умолчанию. |
| [Sort](./sort/)(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) | Сортирует элементы в срезе списка. |
| [Sort](./sort/)(Comparison\<T\>, bool) | Сортирует элементы в списке. |
| [ToArray](./toarray/)() const | Преобразует список в массив. |
| [TrimExcess](./trimexcess/)() | Устанавливает ёмкость списка, соответствующую его размеру. |
| [TrueForAll](./trueforall/)(System::Predicate\<T\>) | Определяет, удовлетворяют ли все элементы коллекции условиям, определённым указанным предикатом. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) | Тип интерфейса. |
| [const_iterator](./const_iterator/) | Тип константного итератора. |
| [const_reverse_iterator](./const_reverse_iterator/) | Тип константного обратного итератора. |
| [IEnumerablePtr](./ienumerableptr/) | Контейнер, содержащий элементы одного типа, который мы используем. |
| [IEnumeratorPtr](./ienumeratorptr/) | Тип [Enumerator](./enumerator/). |
| [iterator](./iterator/) | Тип итератора. |
| [reverse_iterator](./reverse_iterator/) | Тип обратного итератора. |
| [ValueType](./valuetype/) | Этот тип. |
| [vector_t](./vector_t/) | Информация RTTI. |
## Примечания


[List](./) - wrapper around std::vector to be used in translated code. Requires operator == to be impemented for element type. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Создайте первый список.
  auto list1 = MakeObject<List<int>>();

  // Заполните первый список.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Отсортируйте первый список.
  // Элементы первого списка будут: {-5, 1, 3, 8}
  list1->Sort();

  // Удалите элемент с индексом 2.
  // Элементы первого списка будут: {-5, 1, 8}
  list1->RemoveAt(2);

  // Вставьте элемент в индекс 1.
  // Элементы первого списка будут: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Создайте второй список.
  auto list2 = MakeObject<List<int>>();

  // Заполните второй список.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Добавьте элементы из второго списка к первому.
  list1->AddRange(list2);

  // Выведите элементы первого списка.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
This code example produces the following output:
-5 15 1 8 10 20 30
*/
```

## См. также

* Class [Object](../../system/object/)
* Class [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
