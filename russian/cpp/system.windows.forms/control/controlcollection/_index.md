---
title: "Класс System::Windows::Forms::Control::ControlCollection"
linktitle: "ControlCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Windows::Forms::Control::ControlCollection. Коллекция элементов управления. Не реализовано в C++."
type: docs
weight: 200
url: /ru/cpp/system.windows.forms/control/controlcollection/
---
## ControlCollection class


Коллекция элементов управления. Не реализовано.

```cpp
class ControlCollection : public System::Collections::Generic::IList<System::SharedPtr<Control>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Control\>\&) override | Добавляет элемент управления в коллекцию. |
| virtual [AddRange](./addrange/)(System::ArrayPtr\<System::SharedPtr\<Control\>\>) | Добавляет несколько элементов управления в коллекцию. |
| [Clear](./clear/)() override | Удаляет все элементы управления из коллекции. |
| [Contains](./contains/)(const System::SharedPtr\<Control\>\&) const override | Проверяет, присутствует ли конкретный элемент управления в коллекции. |
| virtual [ContainsKey](./containskey/)(System::String) const | Проверяет, присутствует ли элемент управления с определённым именем в коллекции. |
| [ControlCollection](./controlcollection/)(const System::SharedPtr\<Control\>\&) | Конструктор. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Control\>\>, int) override | Копирует содержимое коллекции в существующие элементы массива. |
| [Find](./find/)(const System::String\&, bool) const | Ищет именованный элемент управления в коллекции. При необходимости рекурсивно проверяет коллекции вложенных элементов управления. |
| [get_Count](./get_count/)() const override | Получает количество элементов управления в коллекции. |
| [get_Owner](./get_owner/)() const | Получает элемент управления‑владельца коллекции. |
| [GetChildIndex](./getchildindex/)(const System::SharedPtr\<Control\>\&) const | Ищет конкретный элемент управления. |
| virtual [GetChildIndex](./getchildindex/)(const System::SharedPtr\<Control\>\&, bool) const | Ищет конкретный элемент управления. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель для перебора коллекции. |
| [idx_get](./idx_get/)(int) const override | Доступ по индексу. |
| virtual [idx_get](./idx_get/)(System::String) const | Доступ по имени. |
| [idx_set](./idx_set/)(int, System::SharedPtr\<Control\>) override | Доступ по индексу. |
| virtual [idx_set](./idx_set/)(System::String, System::SharedPtr\<Control\>) | Доступ по имени. |
| [IndexOf](./indexof/)(const System::SharedPtr\<Control\>\&) const override | Ищет элемент управления в коллекции. |
| virtual [IndexOfKey](./indexofkey/)(System::String) const | Ищет именованный элемент управления в коллекции. |
| [Insert](./insert/)(int, const System::SharedPtr\<Control\>\&) override | Вставляет элемент управления в коллекцию. |
| [Remove](./remove/)(const System::SharedPtr\<Control\>\&) override | Удаляет элемент управления из коллекции. |
| [RemoveAt](./removeat/)(int) override | Удаляет элемент управления из коллекции. |
| virtual [RemoveByKey](./removebykey/)(System::String) | Удаляет элемент управления из коллекции. |
| virtual [SetChildIndex](./setchildindex/)(const System::SharedPtr\<Control\>\&, int) | Перемещает элемент управления в новое положение. |
## См. также

* Class [IList](../../../system.collections.generic/ilist/)
* Class [Control](../)
* Namespace [System::Windows::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
