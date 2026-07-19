---
title: "System::Collections::Generic::ISet класс"
linktitle: "ISet"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::ISet класс. Интерфейс коллекции, содержащей набор уникальных элементов. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2700
url: /ru/cpp/system.collections.generic/iset/
---
## ISet class


Интерфейс коллекции, содержащей набор уникальных элементов. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class ISet : public System::Collections::Generic::ICollection<T>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| virtual [ExceptWith](./exceptwith/)(IEnumerablePtr) | Удаляет группу элементов. |
| virtual [IntersectWith](./intersectwith/)(IEnumerablePtr) | Удаляет элементы, отсутствующие в другом контейнере. |
| virtual [IsProperSubsetOf](./ispropersubsetof/)(IEnumerablePtr) | Проверяет, является ли текущий набор строгим подмножеством другого контейнера. |
| virtual [IsProperSupersetOf](./ispropersupersetof/)(IEnumerablePtr) | Проверяет, является ли текущий набор строгим надмножеством другого контейнера. |
| virtual [IsSubsetOf](./issubsetof/)(IEnumerablePtr) | Проверяет, является ли текущий набор подмножеством другого контейнера. |
| virtual [IsSupersetOf](./issupersetof/)(IEnumerablePtr) | Проверяет, является ли текущий набор надмножеством другого контейнера. |
| virtual [Overlaps](./overlaps/)(IEnumerablePtr) | Проверяет, пересекается ли набор с другим контейнером. |
| virtual [SetEquals](./setequals/)(IEnumerablePtr) | Проверяет, содержат ли набор и контейнер одинаковые элементы. |
| virtual [SymmetricExceptWith](./symmetricexceptwith/)(IEnumerablePtr) | Вычисляет симметрическое исключение двух контейнеров. Удаляет все элементы, присутствующие в обоих контейнерах, но одновременно добавляет все элементы, присутствующие в **other**, но отсутствующие в текущем наборе. |
| virtual [UnionWith](./unionwith/)(IEnumerablePtr) | Добавляет элементы из указанной коллекции, которые ещё не присутствуют в текущем наборе. |
| virtual [~ISet](./~iset/)() | Деструктор. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Информация RTTI. |

## См. также

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
