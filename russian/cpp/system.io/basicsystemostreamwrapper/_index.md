---
title: "System::IO::BasicSystemOStreamWrapper класс"
linktitle: "BasicSystemOStreamWrapper"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BasicSystemOStreamWrapper class. Представляет обёртку, похожую на std::ostream, которая использует BasicSystemIOStreamBuf в качестве внутреннего буфера в C++."
type: docs
weight: 700
url: /ru/cpp/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper class


Представляет обёртку, похожую на std::ostream, которая использует [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) в качестве внутреннего буфера.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemOStreamWrapper\&&) | Используется в конструкторе перемещения и операторе перемещающего присваивания для сброса указателей и вызова [swap()](./swap/). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Создаёт новый экземпляр [BasicSystemOStreamWrapper](./). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const BasicSystemOStreamWrapper\&) | Конструктор копирования. Удалён. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(BasicSystemOStreamWrapper\&&) | Конструктор перемещения. |
| [operator=](./operator=/)(const BasicSystemOStreamWrapper\&) | Оператор присваивания копированием. Удалён. |
| [operator=](./operator=/)(BasicSystemOStreamWrapper\&&) | Оператор перемещающего присваивания. |
| [swap](./swap/)(BasicSystemOStreamWrapper\&) | Вызов swap *this и **right**, если они не равны. |
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
