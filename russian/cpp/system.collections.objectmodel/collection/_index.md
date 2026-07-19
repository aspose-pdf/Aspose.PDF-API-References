---
title: "System::Collections::ObjectModel::Collection class"
linktitle: "Collection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::ObjectModel::Collection class. Базовый тип для обобщённой коллекции. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.collections.objectmodel/collection/
---
## Collection class


Базовый тип для обобщённой коллекции. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<class T>class Collection : public System::Collections::Generic::IList<T>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Nested classes

* Class [reverse_iterator_prototype](./reverse_iterator_prototype/)
## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const T\&) override | Добавляет значение в контейнер. |
| [Clear](./clear/)() override | Удаляет все элементы. |
| [Collection](./collection/)() | Создаёт пустую коллекцию. |
| [Collection](./collection/)(SharedPtr\<Generic::IList\<T\>\>) |  |
| [Contains](./contains/)(const T\&) const override | Проверяет, присутствует ли элемент в коллекции. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Копирует элементы коллекции в существующие элементы массива. |
| [crbegin](./crbegin/)() const | Получает обратный итератор к последнему элементу коллекции, квалифицированному как const (первый в обратном порядке). |
| [crend](./crend/)() const | Получает обратный итератор для несуществующего const‑квалифицированного элемента перед началом коллекции. |
| [get_Count](./get_count/)() const override | Получает количество элементов. |
| [get_Items](./get_items/)() | Внутренний аксессор структуры данных. |
| [get_Items](./get_items/)() const | Внутренний аксессор структуры данных. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель для перебора коллекции. |
| [idx_get](./idx_get/)(int) const override | Получает значение по указанному индексу. |
| [idx_set](./idx_set/)(int, T) override | Устанавливает значение по указанному индексу. |
| [IndexOf](./indexof/)(const T\&) const override | Ищет элемент в коллекции. |
| [Insert](./insert/)(int, const T\&) override | Вставляет элемент в указанную позицию. |
| [operator[]](./operator[]/)(int) | Получает значение по указанному индексу. |
| [operator[]](./operator[]/)(int) const | Получает значение по указанному индексу. |
| [rbegin](./rbegin/)() | Получает обратный итератор к последнему элементу коллекции (первый в обратном порядке). |
| [rbegin](./rbegin/)() const | Получает обратный итератор к последнему элементу const‑квалифицированной коллекции (первый в обратном порядке). |
| [Remove](./remove/)(const T\&) override | Удаляет конкретный элемент. |
| [RemoveAt](./removeat/)(int) override | Удаляет элемент в указанной позиции. |
| [rend](./rend/)() | Получает обратный итератор для несуществующего элемента перед началом коллекции. |
| [rend](./rend/)() const | Получает обратный итератор для несуществующего элемента перед началом const‑квалифицированной коллекции. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Делает сохранённые указатели слабыми (если применимо). |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [const_reverse_iterator](./const_reverse_iterator/) |  |
| [reverse_iterator](./reverse_iterator/) |  |

## См. также

* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PDF for C++](../../)
