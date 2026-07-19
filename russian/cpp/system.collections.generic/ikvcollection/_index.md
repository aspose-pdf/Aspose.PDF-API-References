---
title: "System::Collections::Generic::IKVCollection класс"
linktitle: "IKVCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::IKVCollection класс. Интерфейс контейнера, содержащего ключи или значения словарноподобного контейнера. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2500
url: /ru/cpp/system.collections.generic/ikvcollection/
---
## IKVCollection class


Интерфейс контейнера, содержащего ключи или значения словарноподобного контейнера. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class IKVCollection : public System::Collections::Generic::IList<T>
```


| Параметр | Описание |
| --- | --- |
| T | [KeyValuePair](../keyvaluepair/) тип. |
## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const T\&) override | Добавляет элемент в контейнер. |
| [Clear](./clear/)() override | Удаляет все элементы из контейнера. |
| [Contains](./contains/)(const T\&) const override | Проверяет, присутствует ли элемент в контейнере. |
| virtual [get_Count](./get_count/)() const | Возвращает количество элементов в контейнере. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Проверяет, является ли контейнер только для чтения. |
| virtual [GetEnumerator](./getenumerator/)() | Информация RTTI. |
| virtual [idx_get](./idx_get/)(int) const | Функция получения. |
| [idx_set](./idx_set/)(int, T) override | Функция установки. |
| [IndexOf](./indexof/)(const T\&) const override | Возвращает индекс элемента в контейнере. |
| [Insert](./insert/)(int, const T\&) override | Вставляет элемент в указанную позицию. |
| [Remove](./remove/)(const T\&) override | Удаляет элемент из контейнера. |
| [RemoveAt](./removeat/)(int) override | Удаляет элемент в указанной позиции. |

## См. также

* Class [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
