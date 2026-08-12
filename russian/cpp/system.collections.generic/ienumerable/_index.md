---
title: "Класс System::Collections::Generic::IEnumerable"
linktitle: "IEnumerable"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::IEnumerable. Интерфейс объекта, предоставляющего перечислитель по содержащимся элементам в C++."
type: docs
weight: 2200
url: /ru/cpp/system.collections.generic/ienumerable/
---
## IEnumerable class


Интерфейс объекта, предоставляющего перечислитель над содержащимися элементами.

```cpp
template<typename T>class IEnumerable : public virtual System::Object
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [begin](./begin/)() | Получает итератор, указывающий на первый элемент (если он есть) коллекции. Этот итератор нельзя использовать для изменения ссылочного объекта, потому что [GetEnumerator()](./getenumerator/) возвращает копию объекта типа T. |
| [begin](./begin/)() const | Получает итератор, указывающий на первый элемент (если он существует) константно-квалифицированного экземпляра коллекции. |
| [cbegin](./cbegin/)() const | Получает итератор, указывающий на первый константно-квалифицированный элемент (если он существует) коллекции. |
| [cend](./cend/)() const | Получает итератор, указывающий сразу после последнего константно-квалифицированного элемента (если он существует) коллекции. |
| [end](./end/)() | Получает итератор, указывающий сразу после последнего элемента (если он есть) коллекции. Этот итератор нельзя использовать для изменения ссылочного объекта, потому что [GetEnumerator()](./getenumerator/) возвращает копию объекта типа T. |
| [end](./end/)() const | Получает итератор, указывающий сразу после последнего элемента (если он существует) константно-квалифицированного экземпляра коллекции. |
| virtual [GetEnumerator](./getenumerator/)() | Получает перечислитель. |
| [LINQ_Aggregate](./linq_aggregate/)(const Func\<T, T, T\>\&) | Применяет функцию-аккумулятор к последовательности. |
| [LINQ_All](./linq_all/)(std::function\<bool(T)>) | Определяет, удовлетворяют ли все элементы последовательности условию. |
| [LINQ_Any](./linq_any/)() | Определяет, содержит ли последовательность какие-либо элементы. |
| [LINQ_Any](./linq_any/)(std::function\<bool(T)>) | Определяет, существует ли любой элемент последовательности или удовлетворяет условию. |
| [LINQ_Average](./linq_average/)() | Вычисляет среднее значение последовательности числовых значений. |
| [LINQ_Average](./linq_average/)(const Func\<T, ResultType\>\&) | Вычисляет среднее значение последовательности значений, полученных вызовом функции преобразования для каждого элемента входной последовательности. |
| [LINQ_Average](./linq_average/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_Cast](./linq_cast/)() | Преобразует элементы к указанному типу. |
| [LINQ_Cast](./linq_cast/)() |  |
| [LINQ_Concat](./linq_concat/)(SharedPtr\<IEnumerable\<T\>\>) | Объединяет две последовательности. |
| [LINQ_Contains](./linq_contains/)(T) | Определяет, содержит ли последовательность указанное значение. |
| [LINQ_Count](./linq_count/)() | Возвращает количество элементов в последовательности (рассчитанное прямым подсчётом). |
| [LINQ_Count](./linq_count/)(const Func\<T, bool\>\&) | Возвращает количество элементов в последовательности, удовлетворяющих указанному условию. |
| [LINQ_ElementAt](./linq_elementat/)(int) | Возвращает элемент по указанному индексу в последовательности. |
| [LINQ_ElementAtOrDefault](./linq_elementatordefault/)(int) | Возвращает элемент по указанному индексу в последовательности. |
| [LINQ_First](./linq_first/)() | Возвращает первый элемент последовательности. |
| [LINQ_First](./linq_first/)(const Func\<T, bool\>\&) | Возвращает первый элемент последовательности, удовлетворяющий указанному условию. |
| [LINQ_FirstOrDefault](./linq_firstordefault/)() | Возвращает первый элемент последовательности или значение по умолчанию, если последовательность пуста. |
| [LINQ_FirstOrDefault](./linq_firstordefault/)(std::function\<bool(T)>) | Возвращает первый элемент последовательности, удовлетворяющий условию, или значение по умолчанию, если такой элемент не найден. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<T, Key\>) | Группирует элементы последовательности. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<T, Key\>, System::Func\<T, Element\>) | Группирует элементы последовательности. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<Source, Key\>) |  |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<Source, Key\>, System::Func\<Source, Element\>) |  |
| [LINQ_Last](./linq_last/)() | Возвращает последний элемент последовательности. |
| [LINQ_LastOrDefault](./linq_lastordefault/)() | Возвращает последний элемент последовательности или значение по умолчанию, если последовательность пуста. |
| [LINQ_Max](./linq_max/)(const Func\<T, ResultType\>\&) | Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает максимальное полученное значение. |
| [LINQ_Max](./linq_max/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_Min](./linq_min/)(const Func\<T, ResultType\>\&) | Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает минимальное полученное значение. |
| [LINQ_Min](./linq_min/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_OfType](./linq_oftype/)() | Фильтрует элементы последовательности по указанному типу. |
| [LINQ_OfType](./linq_oftype/)() |  |
| [LINQ_OrderBy](./linq_orderby/)(const Func\<T, Key\>\&) | Сортирует элементы последовательности по возрастанию в соответствии со значениями ключей, выбранными функцией keySelector. |
| [LINQ_OrderBy](./linq_orderby/)(const Func\<Source, Key\>\&) |  |
| [LINQ_OrderByDescending](./linq_orderbydescending/)(const Func\<T, Key\>\&) | Сортирует элементы последовательности в порядке убывания согласно значениям ключа, выбранным с помощью keySelector. |
| [LINQ_OrderByDescending](./linq_orderbydescending/)(const Func\<Source, Key\>\&) |  |
| [LINQ_Reverse](./linq_reverse/)() | Инвертирует порядок элементов в последовательности. |
| [LINQ_Select](./linq_select/)(const Func\<T, ResultType\>\&) | Преобразует элементы последовательности. |
| [LINQ_Select](./linq_select/)(const Func\<T, int32_t, ResultType\>\&) | Преобразует каждый элемент последовательности в новую форму, учитывая индекс элемента. |
| [LINQ_Select](./linq_select/)(const Func\<Source, Result\>\&) |  |
| [LINQ_Select](./linq_select/)(const Func\<Source, int32_t, Result\>\&) |  |
| [LINQ_SelectMany](./linq_selectmany/)(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) | Проецирует каждый элемент последовательности и объединяет полученные последовательности в одну. |
| [LINQ_SelectMany](./linq_selectmany/)(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) |  |
| [LINQ_Skip](./linq_skip/)(int32_t) | Пропускает указанное количество последовательных элементов с начала последовательности и возвращает оставшееся. |
| [LINQ_Take](./linq_take/)(int32_t) | Возвращает указанное количество последовательных элементов с начала последовательности. |
| [LINQ_ToArray](./linq_toarray/)() | Создаёт массив из последовательности. |
| [LINQ_ToList](./linq_tolist/)() | Создаёт [List<T>](../list/) из последовательности. |
| [LINQ_Where](./linq_where/)(std::function\<bool(T)>) | Фильтрует последовательность на основе указанного предиката. |
| virtual [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const | Получает реализацию константного итератора begin для текущего контейнера. |
| virtual [virtualizeBeginIterator](./virtualizebeginiterator/)() | Получает реализацию итератора begin для текущего контейнера. |
| virtual [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const | Получает реализацию константного итератора end для текущего контейнера. |
| virtual [virtualizeEndIterator](./virtualizeenditerator/)() | Получает реализацию итератора end для текущего контейнера. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [const_iterator](./const_iterator/) | Тип константного итератора. |
| [IEnumeratorType](./ienumeratortype/) | Информация RTTI. |
| [iterator](./iterator/) | Тип итератора. |
| [ValueType](./valuetype/) |  |
| [virtualized_iterator](./virtualized_iterator/) | Базовый тип внутреннего итератора. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Тип элемента внутреннего итератора. |

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
