---
title: "System::IO::BasicSystemIOStreamBuf класс"
linktitle: "BasicSystemIOStreamBuf"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BasicSystemIOStreamBuf class. Представляет буфер, который оборачивает потоки, похожие на System::IO::Stream, и позволяет использовать их в качестве внутреннего буфера потоков, похожих на std::iostream, в C++."
type: docs
weight: 400
url: /ru/cpp/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf class


Представляет буфер, который оборачивает потоки, похожие на [System::IO::Stream](../stream/), и позволяет использовать их в качестве внутреннего буфера потоков, похожих на std::iostream.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIOStreamBuf\&&) | Используется в конструкторе перемещения и операторе перемещающего присваивания для сброса указателей и вызова [swap()](./swap/). |
| explicit [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Создаёт новый экземпляр [BasicSystemIOStreamBuf](./). |
| explicit [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) | Создаёт новый экземпляр [BasicSystemIOStreamBuf](./). |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const BasicSystemIOStreamBuf\&) | Конструктор копирования. Удалён. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(BasicSystemIOStreamBuf\&&) | Конструктор перемещения. |
| [operator=](./operator=/)(const BasicSystemIOStreamBuf\&) | Оператор присваивания копированием. Удалён. |
| [operator=](./operator=/)(BasicSystemIOStreamBuf\&&) | Оператор перемещающего присваивания. |
| [swap](./swap/)(BasicSystemIOStreamBuf\&) | Вызов swap *this и right, если они не равны. |
| [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Деструктор. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [char_type](./char_type/) |  |
| [int_type](./int_type/) |  |
| [Mysb](./mysb/) |  |
| [off_type](./off_type/) |  |
| [pos_type](./pos_type/) |  |
| [traits_type](./traits_type/) |  |
## См. также

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
