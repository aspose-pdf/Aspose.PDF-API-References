---
title: "System::Collections::IEnumeratorImplRefType класс"
linktitle: "IEnumeratorImplRefType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::IEnumeratorImplRefType класс. Обёртка, создающая необобщённую реализацию IEnumerator над обобщённым итератором IEnumeratorImplRefType — обёртка для ссылочных типов в C++."
type: docs
weight: 700
url: /ru/cpp/system.collections/ienumeratorimplreftype/
---
## IEnumeratorImplRefType class


Обёртка, создающая необобщённую реализацию [IEnumerator](../ienumerator/) над обобщённым итератором [IEnumeratorImplRefType](./) — обёртка для ссылочных типов.

```cpp
template<typename T>class IEnumeratorImplRefType : public System::Collections::IEnumerator
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_Current](./get_current/)() const override | Получает текущий элемент. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<System::SharedPtr\<T\>\>\>) | конструктор обертки |
| [MoveNext](./movenext/)() override | Перемещает перечислитель к следующему элементу. Если ранее ни один элемент не был выбран, устанавливает ссылку на первый доступный элемент. Если достигнут конец контейнера, ничего не делает. |

## См. также

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
