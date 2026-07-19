---
title: "System::Collections::Generic::ICollection класс"
linktitle: "ICollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::ICollection класс. Интерфейс коллекции элементов. Объекты этого класса должны быть выделены только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1900
url: /ru/cpp/system.collections.generic/icollection/
---
## ICollection class


Интерфейс коллекции элементов. Объекты этого класса должны быть выделены только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class ICollection : public virtual System::Collections::Generic::IEnumerable<T>
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Add](./add/)(const T\&) | Добавляет элемент в коллекцию. |
| virtual [Clear](./clear/)() | Удаляет все элементы из коллекции. |
| virtual [Contains](./contains/)(const T\&) const | Проверяет, присутствует ли элемент в коллекции. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) | Копирует все элементы коллекции в существующие элементы массива. |
| virtual [get_Count](./get_count/)() const | Возвращает количество элементов в коллекции. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Проверяет, является ли коллекция только для чтения. |
| [get_SyncRoot](./get_syncroot/)() const | Получает объект, через который синхронизируется коллекция. |
| [ICollection](./icollection/)() | Конструктор по умолчанию. |
| [ICollection](./icollection/)(const ICollection\&) | Конструктор копирования. |
| [ICollection](./icollection/)(ICollection\&&) | Конструктор перемещения. |
| [operator=](./operator=/)(ICollection\&&) | Оператор перемещающего присваивания. |
| [operator=](./operator=/)(const ICollection\&) | Оператор перемещающего присваивания. |
| virtual [Remove](./remove/)(const T\&) | Удаляет элемент из коллекции. |
| virtual [~ICollection](./~icollection/)() | Деструктор. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [ThisType](./thistype/) | Имя типа коллекции. |
| [ValueType](./valuetype/) | Информация RTTI. |

## См. также

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
