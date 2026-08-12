---
title: "System::Span класс"
linktitle: "Span"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Span class. Представляет непрерывный регион произвольной памяти, аналогичный std::span из C++20 в C++."
type: docs
weight: 6000
url: /ru/cpp/system/span/
---
## Span class


Представляет непрерывный регион произвольной памяти, аналогичный std::span из C++20.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span. Этот класс предоставляет типобезопасный способ работы с непрерывными последовательностями объектов. Его можно использовать для обёртывания массивов, стековых массивов или сырых указателей, при этом сохраняется проверка границ. [Span](./) не владеет памятью, на которую указывает — это лишь представление существующей памяти. |
## Методы

| Метод | Описание |
| --- | --- |
| [Clear](./clear/)() const | Очищает содержимое span, устанавливая все элементы в значение по умолчанию. |
| [Fill](./fill/)(const T\&) const | Заполняет span указанным значением. |
| static [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Преобразует массив в [Span](./). |

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
