---
title: "System::Collections::IEnumeratorImplValueType класс"
linktitle: "IEnumeratorImplValueType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::IEnumeratorImplValueType класс. Обертка, которая создает негeneric IEnumerator реализацию над generic Iterator IEnumeratorImplRefType — обертка для value типов в C++."
type: docs
weight: 800
url: /ru/cpp/system.collections/ienumeratorimplvaluetype/
---
## IEnumeratorImplValueType class


Обертка, которая создает негeneric [IEnumerator](../ienumerator/) реализацию над generic Iterator [IEnumeratorImplRefType](../ienumeratorimplreftype/) — обертка для value типов.

```cpp
template<typename T>class IEnumeratorImplValueType : public System::Collections::IEnumerator
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_Current](./get_current/)() const override | Получает текущий элемент. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<T\>\>) | конструктор обертки |
| [MoveNext](./movenext/)() override | Перемещает перечислитель к следующему элементу. Если ранее ни один элемент не был выбран, устанавливает ссылку на первый доступный элемент. Если достигнут конец контейнера, ничего не делает. |

## См. также

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
