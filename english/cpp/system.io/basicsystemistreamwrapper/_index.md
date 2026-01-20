---
title: System::IO::BasicSystemIStreamWrapper class
linktitle: BasicSystemIStreamWrapper
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BasicSystemIStreamWrapper class. Represents a std::istream-like wrapper that used BasicSystemIOStreamBuf as internal buffer in C++.'
type: docs
weight: 600
url: /cpp/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper class


Represents a std::istream-like wrapper that used [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) as internal buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Methods

| Method | Description |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIStreamWrapper\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Constructs a new instance of the [BasicSystemIStreamWrapper](./). |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const BasicSystemIStreamWrapper\&) | Copy constructor. Deleted. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(BasicSystemIStreamWrapper\&&) | Move constructor. |
| [operator=](./operator=/)(const BasicSystemIStreamWrapper\&) | Copy assignment operator. Deleted. |
| [operator=](./operator=/)(BasicSystemIStreamWrapper\&&) | Move assignment operator. |
| [swap](./swap/)(BasicSystemIStreamWrapper\&) | Call to swap *this and **right**, if they are not equal. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
| [traits_type](./traits_type/) |  |
## See Also

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
