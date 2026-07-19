---
title: "System::IO::BasicSystemIOStreamWrapper класс"
linktitle: "BasicSystemIOStreamWrapper"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BasicSystemIOStreamWrapper класс. Представляет обёртку, похожую на std::iostream, которая использует BasicSystemIOStreamBuf в качестве внутреннего буфера в C++."
type: docs
weight: 500
url: /ru/cpp/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper class


Представляет обёртку, похожую на std::iostream, которая использует [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) в качестве внутреннего буфера.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIOStreamWrapper\&&) | Используется в конструкторе перемещения и операторе перемещающего присваивания для сброса указателей и вызова [swap()](./swap/). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Создаёт новый экземпляр [BasicSystemIOStreamWrapper](./). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const BasicSystemIOStreamWrapper\&) | Конструктор копирования. Удалён. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(BasicSystemIOStreamWrapper\&&) | Конструктор перемещения. |
| [operator=](./operator=/)(const BasicSystemIOStreamWrapper\&) | Оператор присваивания копированием. Удалён. |
| [operator=](./operator=/)(BasicSystemIOStreamWrapper\&&) | Оператор перемещающего присваивания. |
| [swap](./swap/)(BasicSystemIOStreamWrapper\&) | Вызов swap *this и **right**, если они не равны. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [char_type](./char_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
| [traits_type](./traits_type/) |  |
## См. также

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
