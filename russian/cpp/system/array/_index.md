---
title: "Класс System::Array"
linktitle: "Массив"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Array. Класс, представляющий структуру данных массива. Объекты этого класса должны создаваться только с помощью функций System::MakeArray() и System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system/array/
---
## Array class


Класс, представляющий структуру данных массива. Объекты этого класса должны создаваться только с помощью функций [System::MakeArray()](../makearray/) и [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива |
## Nested classes

* Class [Enumerator](./enumerator/)
## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const T\&) override | Не поддерживается, поскольку массив, представленный текущим объектом, доступен только для чтения. |
| [Array](./array/)() | Создаёт пустой массив. |
| [Array](./array/)(int, const T\&) | Конструктор заполнения. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) | Конструктор заполнения. |
| [Array](./array/)(int, const T) | Конструктор заполнения. |
| [Array](./array/)(vector_t\&&) | Конструктор перемещения. |
| [Array](./array/)(const vector_t\&) | Конструктор копирования. |
| [Array](./array/)(const std::vector\<Q\>\&) | Создаёт объект [Array](./) и заполняет его значениями, скопированными из объекта std::vector, тип значений которого такой же, как **T**, но отличается от **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::vector\<Q\>\&&) | Создаёт объект [Array](./) и заполняет его значениями, перемещёнными из объекта std::vector, тип значений которого такой же, как **T**, но отличается от **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::initializer_list\<UnderlyingType\>) | Создаёт объект [Array](./) и заполняет его значениями из указанного списка инициализации, содержащего элементы типа **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(const std::array\<UnderlyingType, InitArraySize\>\&) | Создаёт объект [Array](./) и заполняет его значениями из указанного массива, содержащего элементы типа **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::initializer_list\<bool\>, int) | Создаёт объект [Array](./) и заполняет его значениями из указанного списка инициализации, содержащего элементы типа bool. |
| static [AsReadOnly](./asreadonly/)(const SharedPtr\<Array\<T\>\>\&) | Преобразует массив в коллекцию только для чтения. |
| [begin](./begin/)() | Возвращает итератор на первый элемент контейнера. Если контейнер пуст, возвращённый итератор будет равен [end()](./end/). |
| [begin](./begin/)() const | Возвращает итератор на первый элемент константного контейнера. Если контейнер пуст, возвращённый итератор будет равен [end()](./end/). |
| static [BinarySearch](./binarysearch/)(System::ArrayPtr\<T\>, const T\&) | Выполняет бинарный поиск в отсортированном массиве. |
| static [BinarySearch](./binarysearch/)(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) | НЕ РЕАЛИЗОВАНО. |
| [cbegin](./cbegin/)() const | Возвращает итератор на первый элемент, квалифицированный как const, в контейнере. Если контейнер пуст, возвращённый итератор будет равен [cend()](./cend/). |
| [cend](./cend/)() const | Возвращает итератор на элемент, следующий за последним элементом контейнера. Этот элемент служит заполнителем; попытка доступа к нему приводит к неопределённому поведению. |
| [Clear](./clear/)() override | Не поддерживается, поскольку массив, представленный текущим объектом, доступен только для чтения. |
| static [Clear](./clear/)(const ArrayPtr\<Type\>\&, int, int) | Заменяет **count** значений, начиная с индекса **startIndex**, в указанном массиве значениями по умолчанию. |
| [Clone](./clone/)() | Клонирует массив. |
| static [ConstrainedCopy](./constrainedcopy/)(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Копирует диапазон элементов из [System.Array](./), начиная с указанного источника. |
| [Contains](./contains/)(const T\&) const override | Определяет, находится ли указанный элемент в массиве. |
| static [ConvertAll](./convertall/)(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) | Создаёт новый объект [Array](./) и заполняет его элементами указанного массива, преобразованными в тип **OutputType** с помощью указанного делегата‑конвертера. |
| static [ConvertAll](./convertall/)(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) | Создаёт новый объект [Array](./) и заполняет его элементами указанного массива, преобразованными в тип **OutputType** с помощью указанного объект‑функции‑конвертера. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) | Копирует указанное количество элементов из исходного массива в массив‑назначение. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) | Копирует указанное количество элементов из представления исходного массива в массив‑назначение. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) | Копирует указанное количество элементов из исходного массива в представление массива‑назначения. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) | Копирует указанное количество элементов из представления исходного массива в представление массива‑назначения. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) | Копирует указанное количество элементов из массива‑источника в стеке в массив‑назначение. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) | Копирует указанное количество элементов из исходного массива в массив‑назначение в стеке. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) | Копирует указанное количество элементов из массива‑источника в стеке в массив‑назначение в стеке. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Копирует указанное количество элементов из исходного массива, начиная с указанного индекса, в указанную позицию массива‑назначения. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Копирует указанное количество элементов из представления исходного массива, начиная с указанного индекса, в указанную позицию массива‑назначения. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) | Копирует указанное количество элементов из исходного массива, начиная с указанного индекса, в указанную позицию представления массива‑назначения. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) | Копирует указанное количество элементов из представления исходного массива, начиная с указанного индекса, в указанную позицию представления целевого массива. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Копирует указанное количество элементов из исходного массива в стеке, начиная с указанного индекса, в указанную позицию целевого массива. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) | Копирует указанное количество элементов из исходного массива, начиная с указанного индекса, в указанную позицию целевого массива в стеке. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) | Копирует указанное количество элементов из исходного массива в стеке, начиная с указанного индекса, в указанную позицию целевого массива в стеке. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) | Копирует указанное количество элементов из представления исходного массива, начиная с указанного индекса, в указанную позицию целевого массива в стеке. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Копирует все элементы текущего массива в указанный целевой массив. Элементы вставляются в целевой массив, начиная с индекса, указанного аргументом arrayIndex. |
| [CopyTo](./copyto/)(const ArrayPtr\<DstType\>\&, int64_t) const | Копирует все элементы текущего массива в указанный целевой массив. Элементы вставляются в целевой массив, начиная с индекса, указанного аргументом dstIndex. |
| [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, int64_t) const | Копирует все элементы текущего массива в указанное представление целевого массива. Элементы вставляются в представление целевого массива, начиная с индекса, указанного аргументом dstIndex. |
| [CopyTo](./copyto/)(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const | Копирует указанное количество элементов из текущего массива, начиная с указанной позиции, в указанный целевой массив. Элементы вставляются в целевой массив, начиная с индекса, указанного аргументом dstIndex. |
| [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const | Копирует указанное количество элементов из текущего массива, начиная с указанной позиции, в указанное представление целевого массива. Элементы вставляются в представление целевого массива, начиная с индекса, указанного аргументом dstIndex. |
| [Count](./count/)() const | Возвращает число, представляющее общее количество всех элементов во всех измерениях массива. |
| [crbegin](./crbegin/)() const | Возвращает обратный итератор на первый элемент обратного контейнера. Он соответствует последнему элементу обычного контейнера. Если контейнер пуст, возвращённый итератор будет равен [crend()](./crend/). |
| [crend](./crend/)() const | Возвращает обратный итератор к элементу, следующему за последним элементом перевёрнутого контейнера. Он соответствует элементу, предшествующему первому элементу неперевёрнутого контейнера. Этот элемент служит заполнителем; попытка доступа к нему приводит к неопределённому поведению. |
| [data](./data/)() | Возвращает ссылку на внутреннюю структуру данных, используемую для хранения элементов массива. |
| [data](./data/)() const | Возвращает константную ссылку на внутреннюю структуру данных, используемую для хранения элементов массива. |
| [data_ptr](./data_ptr/)() | Возвращает необработанный указатель на начало буфера памяти, где хранятся элементы массива. |
| [data_ptr](./data_ptr/)() const | Возвращает константный необработанный указатель на начало буфера памяти, где хранятся элементы массива. |
| [end](./end/)() | Возвращает итератор на элемент, следующий за последним элементом контейнера. Этот элемент служит заполнителем; попытка доступа к нему приводит к неопределённому поведению. |
| [end](./end/)() const | Возвращает итератор к элементу, следующему за последним элементом контейнера с const‑квалификатором. Этот элемент служит заполнителем; попытка доступа к нему приводит к неопределённому поведению. |
| static [Exists](./exists/)(ArrayPtr\<T\>, std::function\<bool(T)>) | Определяет, содержит ли указанный объект [Array](./) элемент, удовлетворяющий требованиям указанного предиката. |
| static [Find](./find/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Ищет первый элемент в указанном массиве, который удовлетворяет условиям указанного предиката. |
| static [FindAll](./findall/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Получает все элементы, соответствующие условиям, определённым указанным предикатом. |
| static [FindIndex](./findindex/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Ищет первый элемент в указанном массиве, который удовлетворяет условиям указанного предиката. |
| static [ForEach](./foreach/)(const ArrayPtr\<T\>\&, System::Action\<T\>) | Выполняет указанное действие для каждого элемента указанного массива. |
| [get_Count](./get_count/)() const override | Возвращает размер массива. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Указывает, является ли массив только для чтения. |
| [get_Length](./get_length/)() const override | Возвращает 32‑битное целое число, представляющее общее количество всех элементов во всех измерениях массива. |
| [get_LongLength](./get_longlength/)() const | Возвращает 64‑битное целое число, представляющее общее количество всех элементов во всех измерениях массива. |
| [get_Rank](./get_rank/)() const | НЕ РЕАЛИЗОВАНО. |
| [GetEnumerator](./getenumerator/)() override | Возвращает указатель на объект [Enumerator](./enumerator/), предоставляющий интерфейс IEnumerator к элементам массива, представленного текущим объектом. |
| [GetLength](./getlength/)(int) | Возвращает количество элементов в указанном измерении. |
| [GetLongLength](./getlonglength/)(int) | Возвращает количество элементов в указанном измерении как 64‑битное целое число. |
| [GetLowerBound](./getlowerbound/)(int) const | Возвращает нижнюю границу указанного измерения. |
| [GetSizeTLength](./getsizetlength/)() const | Возвращает переменную std::size_t, представляющую общее количество всех элементов во всех измерениях массива. |
| [GetUpperBound](./getupperbound/)(int) | Возвращает верхнюю границу указанного измерения. |
| [idx_get](./idx_get/)(int) const override | Возвращает элемент по указанному индексу. |
| [idx_set](./idx_set/)(int, T) override | Устанавливает указанное значение как элемент массива по указанному индексу. |
| [IndexOf](./indexof/)(const T\&) const override | Определяет индекс первого вхождения указанного элемента в массив. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&) | Определяет индекс первого вхождения указанного элемента в массив. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) | Определяет индекс первого вхождения указанного элемента в массив, начиная с указанного индекса. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) | Определяет индекс первого вхождения указанного элемента в диапазоне элементов массива, заданном стартовым индексом и количеством элементов в диапазоне. |
| [Init](./init/)(const T) | Заполняет массив, представленный текущим объектом, значениями из указанного массива. |
| [Initialize](./initialize/)() | Заполняет массив объектами типа **T**, созданными по умолчанию. |
| [Insert](./insert/)(int, const T\&) override | Не поддерживается, поскольку массив, представленный текущим объектом, доступен только для чтения. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) | Определяет индекс последнего вхождения указанного элемента в диапазоне элементов массива, заданном стартовым индексом и количеством элементов в диапазоне. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) | Определяет индекс последнего вхождения указанного элемента в массив, начиная с указанного индекса. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&) | Определяет индекс последнего вхождения указанного элемента в массив. |
| [Max](./max/)() const | Находит наибольший элемент в массиве, используя [operator<()](../operator_/) для сравнения элементов. |
| [Min](./min/)() const | Находит наименьший элемент в массиве, используя [operator<()](../operator_/) для сравнения элементов. |
| [operator[]](./operator[]/)(int) | Возвращает элемент по указанному индексу. |
| [operator[]](./operator[]/)(int) const | Возвращает элемент по указанному индексу. |
| [raw_data_ptr](./raw_data_ptr/)() override | Возвращает указатель на первый элемент одноразмерного массива. Для многомерных массивов результат неопределён. |
| [rbegin](./rbegin/)() | Возвращает обратный итератор к первому элементу перевёрнутого контейнера. Он соответствует последнему элементу неперевёрнутого контейнера. Если контейнер пуст, возвращаемый итератор равен [rend()](./rend/). |
| [rbegin](./rbegin/)() const | Возвращает обратный итератор к первому элементу перевёрнутого контейнера. Он соответствует последнему элементу неперевёрнутого контейнера. Если контейнер пуст, возвращаемый итератор равен [rend()](./rend/). |
| [Remove](./remove/)(const T\&) override | Не поддерживается, поскольку массив, представленный текущим объектом, доступен только для чтения. |
| [RemoveAt](./removeat/)(int) override | Не поддерживается, поскольку массив, представленный текущим объектом, доступен только для чтения. |
| [rend](./rend/)() | Возвращает обратный итератор к элементу, следующему за последним элементом перевёрнутого контейнера. Он соответствует элементу, предшествующему первому элементу неперевёрнутого контейнера. Этот элемент служит заполнителем; попытка доступа к нему приводит к неопределённому поведению. |
| [rend](./rend/)() const | Возвращает обратный итератор к элементу, следующему за последним элементом перевёрнутого контейнера. Он соответствует элементу, предшествующему первому элементу неперевёрнутого контейнера. Этот элемент служит заполнителем; попытка доступа к нему приводит к неопределённому поведению. |
| static [Resize](./resize/)(ArrayPtr\<Type\>\&, int) | Изменяет размер указанного массива до заданного значения или создает новый массив с указанным размером. |
| static [Reverse](./reverse/)(const ArrayPtr\<Type\>\&) | Разворачивает элементы в указанном массиве. |
| static [Reverse](./reverse/)(const ArrayPtr\<Type\>\&, int, int) | Разворачивает диапазон элементов в указанном массиве. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Заставляет массив рассматривать сохранённые указатели как слабые (если применимо). |
| [SetValue](./setvalue/)(const T\&, int) | Устанавливает значение элемента по указанному индексу. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&) | Сортирует элементы в указанном массиве, используя сравниватель по умолчанию. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, int, int) | Сортирует диапазон элементов в указанном массиве, используя сравниватель по умолчанию. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) | Сортирует элементы в указанном массиве, используя указанный сравниватель. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) | НЕ РЕАЛИЗОВАНО. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) | Сортирует элементы в указанном массиве, используя указанное сравнение. |
| static [Sort](./sort/)(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) | Сортирует два массива, один содержащий ключи и другой - соответствующие элементы, основываясь на значениях массива, содержащего ключи, элементы которого сравниваются с помощью оператора<. |
| static [Sort](./sort/)(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) | Сортирует два массива, один содержащий ключи и другой - соответствующие элементы, основываясь на значениях массива, содержащего ключи, элементы которого сравниваются с помощью сравнивателя по умолчанию. |
| static [TrueForAll](./trueforall/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Определяет, удовлетворяют ли все элементы в указанном массиве условиям, определённым указанным предикатом. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [const_iterator](./const_iterator/) | Тип константного итератора. |
| [const_reverse_iterator](./const_reverse_iterator/) | Тип константного обратного итератора. |
| [EnumerablePtr](./enumerableptr/) | Псевдоним для типа умного указателя, указывающего на объект IEnumerable, содержащий элементы типа **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Псевдоним для типа умного указателя, указывающего на объект IEnumerator, содержащий элементы типа **T**. |
| [iterator](./iterator/) | Тип итератора. |
| [reverse_iterator](./reverse_iterator/) | Тип обратного итератора. |
| [UnderlyingType](./underlyingtype/) | Псевдоним типа, используемого для представления каждого элемента массива. |
| [ValueType](./valuetype/) | Псевдоним типа элементов массива. |
## Примечания



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Создайте и заполните массив.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Выведите элементы массива.
  Print(arrayPtr);

  // Отсортировать элементы массива по возрастанию.
  Array<int32_t>::Sort(arrayPtr);

  // Выведите элементы массива.
  Print(arrayPtr);

  // Вывести количество элементов массива.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Вывести индекс элемента, равного 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Изменить размер массива.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Выведите элементы массива.
  Print(arrayPtr);

  return 0;
}
/*
This code example produces the following output:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## См. также

* Class [ArrayBase](../arraybase/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
