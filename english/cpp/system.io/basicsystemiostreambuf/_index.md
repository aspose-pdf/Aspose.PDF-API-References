---
title: System::IO::BasicSystemIOStreamBuf class
linktitle: BasicSystemIOStreamBuf
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BasicSystemIOStreamBuf class. Represents a buffer that wraps System::IO::Stream-like streams and allows them to be used as an std::iostream-like streams internal buffer in C++.'
type: docs
weight: 400
url: /cpp/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf class


Represents a buffer that wraps [System::IO::Stream](../stream/)-like streams and allows them to be used as an std::iostream-like streams internal buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Methods

| Method | Description |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIOStreamBuf\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
| explicit [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Constructs a new instance of the [BasicSystemIOStreamBuf](./). |
| explicit [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) | Constructs a new instance of the [BasicSystemIOStreamBuf](./). |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const BasicSystemIOStreamBuf\&) | Copy constructor. Deleted. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(BasicSystemIOStreamBuf\&&) | Move constructor. |
| [operator=](./operator=/)(const BasicSystemIOStreamBuf\&) | Copy assignment operator. Deleted. |
| [operator=](./operator=/)(BasicSystemIOStreamBuf\&&) | Move assignment operator. |
| [swap](./swap/)(BasicSystemIOStreamBuf\&) | Call to swap *this and right, if they are not equal. |
| [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [int_type](./int_type/) |  |
| [Mysb](./mysb/) |  |
| [off_type](./off_type/) |  |
| [pos_type](./pos_type/) |  |
| [traits_type](./traits_type/) |  |
## See Also

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
