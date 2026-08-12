---
title: "System::Collections::BitArray класс"
linktitle: "BitArray"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::BitArray класс. Массив битов, к которым можно обращаться по индексу. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.collections/bitarray/
---
## BitArray class


[Array](../../system/array/) of bits which can be addressed by index. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BitArray : public virtual System::Object,
                 public System::Collections::Generic::ICollection<bool>
```

## Nested classes

* Class [Enumerator](./enumerator/)
* Class [Reference](./reference/)
## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const bool\&) override | Добавляет значение в конец контейнера. |
| [And](./and/)(const BitArrayPtr\&) | Вычисляет побитовое 'and' между двумя BitSet. |
| [BitArray](./bitarray/)(const bitset\&) | Конструктор копирования. |
| [BitArray](./bitarray/)(const BitArray\&) | Конструктор копирования. |
| [BitArray](./bitarray/)(const BitArrayPtr\&) | Конструктор копирования. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<bool\>\&) | Конструктор копирования. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<uint8_t\>\&) | Конструктор копирования. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<int\>\&) | Конструктор копирования. |
| [BitArray](./bitarray/)(int, bool) | Заполняющий конструктор. |
| [Clear](./clear/)() override | Удаляет все элементы. |
| [Contains](./contains/)(const bool\&) const override | Проверяет, присутствует ли конкретное значение в контейнере. Не реализовано. |
| [CopyTo](./copyto/)(System::ArrayPtr\<bool\>, int) override | Копирует данные в существующие элементы массива. |
| [data](./data/)() | Доступ к базовой структуре данных. |
| [data](./data/)() const | Доступ к базовой структуре данных. |
| [Get](./get/)(int) const | Получает элемент [BitArray](./). |
| [get_Count](./get_count/)() const override | Получает размер контейнера. |
| [get_Length](./get_length/)() const | Получает размер контейнера. |
| [GetEnumerator](./getenumerator/)() override | Создает объект перечислителя. |
| [idx_get](./idx_get/)(int) const | Функция получения. |
| [idx_set](./idx_set/)(int, bool) | Функция установки. |
| [Not](./not/)() | Отрицает BitSet. |
| [operator!=](./operator!=/)(const BitArray\&) const | Побитовый оператор сравнения. |
| [operator==](./operator==/)(const BitArray\&) const | Побитовый оператор сравнения. |
| [operator[]](./operator[]/)(int) | Функция доступа. |
| [Or](./or/)(const BitArrayPtr\&) | Вычисляет побитовое 'или' между двумя BitSet. |
| [Remove](./remove/)(const bool\&) override | Возвращает первое вхождение указанного значения. Не реализовано. |
| [Set](./set/)(int, bool) | Устанавливает элемент [BitArray](./). |
| [SetAll](./setall/)(bool) | Устанавливает все элементы в указанное значение. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Формальная реализация механизма слабых аргументов шаблона; неприменимо к этому классу. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
| [Xor](./xor/)(const BitArrayPtr\&) | Вычисляет побитовое 'исключающее или' между двумя BitSet. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [bitset](./bitset/) | Информация RTTI. |
## Примечания



```cpp
#include <system/collections/bitarray.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void Print(const System::SmartPtr<System::Collections::Generic::IEnumerable<bool>> &bitArray)
{
  for (const auto item: bitArray)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Создает новый экземпляр класса BitArray.
  auto bitArray = MakeObject<System::Collections::BitArray>(3);

  // Печать значений.
  Print(bitArray);

  return 0;
}
/*
This code example produces the following output:
0 0 0
*/
```

## См. также

* Class [Object](../../system/object/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
