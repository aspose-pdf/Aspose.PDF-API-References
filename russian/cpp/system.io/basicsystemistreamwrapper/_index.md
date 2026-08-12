---
title: "Класс System::IO::BasicSystemIStreamWrapper"
linktitle: "BasicSystemIStreamWrapper"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::IO::BasicSystemIStreamWrapper. Представляет обёртку, похожую на std::istream, которая использует BasicSystemIOStreamBuf в качестве внутреннего буфера в C++."
type: docs
weight: 600
url: /ru/cpp/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper class


Представляет обёртку, похожую на std::istream, которая использует [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) в качестве внутреннего буфера.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIStreamWrapper\&&) | Используется в конструкторе перемещения и операторе перемещающего присваивания для сброса указателей и вызова [swap()](./swap/). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Создаёт новый экземпляр [BasicSystemIStreamWrapper](./). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const BasicSystemIStreamWrapper\&) | Конструктор копирования. Удалён. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(BasicSystemIStreamWrapper\&&) | Конструктор перемещения. |
| [operator=](./operator=/)(const BasicSystemIStreamWrapper\&) | Оператор присваивания копированием. Удалён. |
| [operator=](./operator=/)(BasicSystemIStreamWrapper\&&) | Оператор перемещающего присваивания. |
| [swap](./swap/)(BasicSystemIStreamWrapper\&) | Вызов swap *this и **right**, если они не равны. |
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
