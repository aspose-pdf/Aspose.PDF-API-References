---
title: System::IO::BasicSystemOStreamWrapper class
linktitle: BasicSystemOStreamWrapper
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BasicSystemOStreamWrapper class. Represents a std::ostream-like wrapper that used BasicSystemIOStreamBuf as internal buffer in C++.'
type: docs
weight: 700
url: /cpp/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper class


Represents a std::ostream-like wrapper that used [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) as internal buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Methods

| Method | Description |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemOStreamWrapper\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Constructs a new instance of the [BasicSystemOStreamWrapper](./). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const BasicSystemOStreamWrapper\&) | Copy constructor. Deleted. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(BasicSystemOStreamWrapper\&&) | Move constructor. |
| [operator=](./operator=/)(const BasicSystemOStreamWrapper\&) | Copy assignment operator. Deleted. |
| [operator=](./operator=/)(BasicSystemOStreamWrapper\&&) | Move assignment operator. |
| [swap](./swap/)(BasicSystemOStreamWrapper\&) | Call to swap *this and **right**, if they are not equal. |
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
