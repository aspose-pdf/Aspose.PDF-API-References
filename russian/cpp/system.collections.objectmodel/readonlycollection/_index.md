---
title: "System::Collections::ObjectModel::ReadOnlyCollection класс"
linktitle: "ReadOnlyCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::ObjectModel::ReadOnlyCollection класс. Оборачивает конкретный контейнер для доступа к нему в режиме только для чтения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.collections.objectmodel/readonlycollection/
---
## ReadOnlyCollection class


Оборачивает конкретный контейнер для доступа к нему в режиме только для чтения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class ReadOnlyCollection : public virtual System::Object,
                                               public System::Collections::Generic::IList<T>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [Contains](./contains/)(const T\&) const override | Проверяет, содержит ли контейнер конкретный элемент. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) override | Копирует элементы контейнера в существующие элементы массива. |
| [get_Count](./get_count/)() const override | Получает количество элементов контейнера. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Проверяет, является ли коллекция только для чтения. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель коллекции. |
| [idx_get](./idx_get/)(int) const override | Получает элемент в указанной позиции. |
| [IndexOf](./indexof/)(const T\&) const override | Ищет конкретный элемент в коллекции. |
| [ReadOnlyCollection](./readonlycollection/)(const SharedPtr\<Generic::IList\<T\>\>\&) | Оборачивает только‑для‑чтения коллекцию вокруг конкретной коллекции. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Ничего не делает, так как только‑для‑чтения коллекция лишь оборачивает данные и ничего не хранит. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) | Реализованный интерфейс. |
| [IEnumeratorPtr](./ienumeratorptr/) | Контейнер одинаковых элементов. |
| [ValueType](./valuetype/) | Тип значения. |

## См. также

* Class [Object](../../system/object/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PDF for C++](../../)
