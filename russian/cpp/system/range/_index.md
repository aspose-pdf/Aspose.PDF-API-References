---
title: "System::Range класс"
linktitle: "Range"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Range класс. Представляет диапазон с начальным и конечным индексом. Этот тип должен выделяться в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 5500
url: /ru/cpp/system/range/
---
## Range class


Представляет диапазон с начальным и конечным индексом. Этот тип должен выделяться в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Методы

| Метод | Описание |
| --- | --- |
| static [EndAt](./endat/)(const Index\&) | Создает диапазон, который начинается с начала коллекции и заканчивается указанным конечным индексом. |
| [Equals](./equals/)(const Range\&) const | Определяет, равен ли текущий диапазон указанному диапазону. |
| static [get_All](./get_all/)() | Возвращает [Range](./), представляющий всю коллекцию. |
| [get_End](./get_end/)() const | Получает конечный индекс. |
| [get_Start](./get_start/)() const | Получает начальный индекс. |
| [GetHashCode](./gethashcode/)() const | Возвращает хеш‑код для текущего диапазона. |
| [GetOffsetAndLength](./getoffsetandlength/)(int32_t) const | Вычисляет нулевой смещение начала и длину для указанной длины коллекции. |
| [Range](./range/)() | Создаёт пустой диапазон. |
| [Range](./range/)(const Index\&, const Index\&) | Создаёт [Range](./) из указанных начального и конечного индексов. |
| static [StartAt](./startat/)(const Index\&) | Создает диапазон, который начинается с указанного начального индекса и продолжается до конца коллекции. |
## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
